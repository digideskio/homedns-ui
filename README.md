# HomeDNS-UI

HomeDNS-UI is a web interface for a set of non-public web APIs on top of BIND.  
It's **currently in developement stage and not ready for use**.

## Dependencies
This is the list of the current dependencies installed with bower:
```
├─┬ bootstrap#3.3.7 extraneous (latest is 4.0.0-alpha.4)
│ └── jquery#3.1.0
├─┬ dynatable#0.3.1 extraneous
│ └── jquery#3.1.0
├── moment#2.14.1 extraneous
└── numeral#1.5.3 extraneous
```

## Configuration
All the confguration paramter go to **config.js**.  
So far the only neede parameter is:
 * **baseURL**: The URL of the web APIs.

## TODO
 * **Complete UI**
   * Missing button to delete zones
   * Missing botton mask to create zones
  * **Complete UX**
    * Better error handling
    * Add behaviors for missing UI elements
  * **Internal logic**
    * Validate values
    * Improve logging
  * **General**
    * Code cleanup

