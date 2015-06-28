# Activities [/odata/Activities{?ODataOptions}]

## Retrieve Activities [GET]
Retrieves a list of **Activities**.

+ Parameters
    + $filter (optional, string) ... OData filter string
    + $expand (optional, string) ... 

+ Response 200 (application/json)    
        {
    "odata.metadata": "http://localhost:49863/odata/$metadata#Activities",
    "value": [

        {
            "Id": "e3dab49e-c169-445b-834e-013949fac7cb",
            "ActivityGroupId": "569651df-c975-4917-8202-0af2715bacd1",
            "PatientId": "00000000-0000-0000-0000-000000000000",
            "SiteId": "0f61b19b-33b3-4043-8063-8b7d38b797f4",
            "TeamId": "c079d9bc-9153-4704-b557-2a97cada11f6",
            "StatusId": "00000000-0000-0000-0000-000000000000",
            "IsDeleted": false,
            "Data": "    { \"Id\": 458, \"ActivityGroup\": \"Medication\", \"ParentActivityGroups\": [ \"Morning Clinic\" ], \"PatientFirstName\": \"Camilla\", \"PatientLastName\": \"Reyes\", \"PatientFullName\": \"Reyes, Camilla\", \"PatientGender\": \"Female\", \"PatientDOB\": \"1976-07-23T00:00:00.000Z\", \"PatientNumber\": \"PN2297264\", \"Site\": \"Sydney\", \"Team\": \"City D Team\", \"TreatingDoctor\": \"Gee\", \"Program\": \"Frozen embryo transfer\", \"ProgramDay1\": \"2014-10-10T00:00:00.000Z\", \"Arrival Time\": \"2000-01-01T07:12:00.000Z\", \"Status\": \"Busy other queue\" }"

        }
    ]

}