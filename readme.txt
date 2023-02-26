We will study

1. Material UI
2. Adavnce react
    1. Folder and File structure
    2. hooks
    3. rest api
3. Security
4. Google Map api
5. Rapid api


Issue and Resolve Steps :

(1) 
Issue :
Material UI installation was not working for React 18 + for below command . 
npm install @material-ui/core @material-ui/icons @material-ui/lab

Resolve steps :
react 18+  version supports below command to install Material UI (MUI)

 npm install @mui/material @emotion/react @emotion/styled --legacy-peer-deps
 npm install @mui/icons-material --legacy-peer-deps
 npm install  @mui/lab @react-google-maps/api axios google-map-react