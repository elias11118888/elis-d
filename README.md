This repository defines a JavaScript/React-based project named elis d, structured as a top-level controller package wrapping a nested Create 
React App (CRA) application located under elisdirectrix/. The inner CRA project (elisdirectrix) contains all web client assets, build configuration, testing setup, 
and runtime entry points, while the top-level project delegates its lifecycle scripts (start, build, test) to the nested app.

The project uses React and ReactDOM version ^19.2.6 as core dependencies, is bootstrapped by react-scripts 5.0.1, and follows standard CRA conventions for public 
assets, manifests, performance metrics, and testing utilities.
