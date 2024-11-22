# Javascript Debugger
## 1. Common method we follow
    - console.log()
    - Chrome debug Tool

## 2. How about we do the same thing in IDE?
    - possible?
    - anyone set it up before?
    - how hard is it to configure?

## 3. Set up javascript debugger in vs-code editor (for a sample project)
    1. git clone git@github.com:mokammeltanvir/Calculator-Vue.git
    2. cd Calculator-Vue
    3. npm install
    4. npm run dev 
    // configure javascript debugger for it
    5. Go to Run > Start Debugging > (select chrome) (it will create a launch.json config file)
    6. set 'url: <url-of-frontend-being-served>'
    7. Navigate to Run and Debug options in the left side bar and start 'Lauch chrome against localhost'
    8. Your javascript debugger is started.

## 3. Set up javascript debugger in intellij (for a sample project)
    1. Repeat the steps from 1-4 in the above point no3
    // configure javascript debugger for it
    2. Go to Run > Debug
    3. click edit configurations
    4. Add new configuration for javascript debug
    5. Add `Name`, `URL: <url-of-frontend-being-served>'` , Browser as `chrome` and check on `Ensure breakpoints ...`
    6. Apply and click debug and your javascript debug is started.


## 4. Enjoy