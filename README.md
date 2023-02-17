# Student Enrollment Form
Description
JSONPowerDB is a High Performance, Light Weight, Ajax Enabled, Serverless, Simple to Use, Real-time Database. Easy and fast to develop database applications without using any server side programming / scripting or without installing any kind of database.It is a student registration form that stores the user's data in JSONPowerDB. It supports REST APIs and serverless technology. Students can be added, updated based on their roll number. In this form, the roll number is automatically checked and by the help of API, the data entered into other input fields sothat the user can update accordingly. The application uses AJAX requests for smooth and fast interaction. All kinds of data can be stored, such as numbers, strings, dates, etc.

It is basically a Database Server with Developer friendly REST API services. JPDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

# Benefits Of Using JSONPowerDB:
It is realtime and simple to use. Easy to maintain the reconds.
Serverless support - fast development - cuts time to market. 
Build using world's fastest indexing engine PowerIndex which gives unlimited data capacity, supporting unlimited indexes, realtime data processing which makes it fast and secure. Give developer friendly Webservices API which reduce the developement cost. Multiple Security Layers. Schema free - easy to maintain A single instance - Million Indexes Inbuilt support for querying multiple databases. It is light weight. It is a serverless database so that you don't have to choose an instance size at all.

# Use cases:
All RDMS use cases. All key-value use cases. All document use cases. Time series/geospatial analytics. Real time application for data analytics. Live working HTML templates. Any software application that needs backend DB. (Dynamic web-apps/Mobile/Desktop Apps)

# Release History
JsonPowerDB Version: 2.0

Execute API var baseUrl = "http://api.login2explore.com:5577"; function executeCommand(reqString, apiEndPointUrl) { var url = baseUrl + apiEndPointUrl; var jsonObj;

$.post(url, reqString, function (result) {
    jsonObj = JSON.parse(result);
}).fail(function (result) {
    var dataJsonObj = result.responseText;
    jsonObj = JSON.parse(dataJsonObj);
});
return jsonObj;
} Create a PUT Request String function createPUTRequest(connToken, jsonObj, dbName, relName) { var putRequest = "{\n" + ""token" : "" + connToken + ""," + ""dbName": "" + dbName + "",\n" + ""cmd" : "PUT",\n" + ""rel" : "" + relName + ""," + ""jsonStr": \n" + jsonObj + "\n" + "}"; return putRequest; }

Features
Simple to Use Fast Response Detailed User Interface Tech Stack Client: HTML,CSS,Javascript

Server: JsonPowerDB

Screenshots
http://localhost:8383/Studentform/index.html
