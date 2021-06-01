# FHIRContest
FHIR Contest using Basic Robot Interface

The principle of this project is to demonstrate the flow of FHIR Messages from a Doctor to a Pharmacist to a Pharmacy Robot that dispenses the Medications and sends the appropriate message back to the Pharmacist. The FHIR Messages are stord in the FHIRaaS server.

I need lessons in using GIT

I have loaded all of the Robot and Inventory/Stock Classes and data into my NiPaRobotica Foundation Production. I have inherited some HS classes into Robot.FHIR.* classes. The purpose of these are to support a Rest Dispatcher that will pass FHIR Requests into the production where they will be processed into Robot dialogues etc.. Then I want a FHIR HTTP Client that will post Patient, Medications, Medication Request/Response and Medication Statement Resources into the FHIRaaS server.

I IRIS for Health 2019 I used HS.FHIR.Server as a Business Process that the FHIR Service would send FHIR Request Messages to and then we were able to over ride the logic of the class to do different things depending on the resource being processed. I see that that class has been deprecated and it says to use the HS.FHIRService classes but I can't find the one class that would behave in the same way as the original HS.FHIR.Service class.

I need to set up the Rest Dispatcher routes or my inbound Service (though I might use direct invocation from CSP/Zen form if I have time).. I will do mare after work today.
