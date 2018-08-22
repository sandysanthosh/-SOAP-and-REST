Welcome to the SOAP-Web-Service wiki!

wsdl 
web service descrption language

definition
types
message
operation
porttype

->soap tested using soapUI Tool


type: user profile web service

definition:
request name : string user name
message:input,output
operation: methods in programming lanuage
porttype: root element 

name space

binding  name=?
service element=?

serice:
->url how the 

wsdl to  java:

test the web service:

soap ui:

wsdl 2.0 contrast web service:

xml based document:

java:

definition:

soap:addresslcoation="http://"

<binding name="tempratue" type="tns:temperatureconvertpr">

<port type="temperatur convertor">

<operations name="celsiustofaragin">

<input message="tns:celsiustofaren">
<output message="tns:celsutofaremresponse>

</opertion>


<message>
<part name="tns:celsiustofaren">
</message>

<types>
<xsd:schema>

<types>
<xsd:schema>
<xsd:import namespace="http://ws.craryon.com/" schema location="http://localhost:8081/tempconv?xsd=1"/>
</xsd:schema>
<types>

->wsdl generate artifactes


4 types:

<envelope>
header
body->error-code
</envelope>



<?xml version="1.0"?>

<soap:Envelope
xmlns:soap="http://www.w3.org/2003/05/soap-envelope/"
soap:encodingStyle="http://www.w3.org/2003/05/soap-encoding">

<soap:Header>
...
</soap:Header>

<soap:Body>
...
  <soap:Fault>
  ...
  </soap:Fault>
</soap:Body>

</soap:Envelope>






xmlns:amz="http://www.amzaon.com/order"
xmlns:ebay="http://www.amzaon.com/order"


namespace xml:
xmlns:
prefix:amz

<order xmlns:amz="http://www.amzaon.com/order">
<amz:lineitem/>
<amz:shippingaddress/>


<order xmlns:ebay="http://www.amzaon.com/order">
<amz:lineitem/>
<amz:shippingaddress/>

