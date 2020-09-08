# DataFillBOT
This is a UiPath Studio Project. Open project.json from UiPath Studio or run DataFillBOT.xaml via command line.
For this BOT to work the following Web Application must be hosted on Apache Tomcat Server at port 8080: https://github.com/maazusmani224/QuestionForm
A postgreSQL Database named "QuestionDatabase" must be hosted on port 5432.
This BOT is a part of project for developing a DataEntry BOT that is trigerred by an email having input document attached.
The BOT  opens an MS Ecel File and reads data from it and fills it in the above said Web Application containing a Web Form.
