# SwearJar

{

  "intents": [

    {

      "intent": "HasSworn",

      "slots": [

        {

          "name": "Person",

          "type": "AMAZON.US_FIRST_NAME"

        }

      ]

    },
    
    {

      "intent": "AddPerson",

      "slots": [

        {

          "name": "Person",

          "type": "AMAZON.US_FIRST_NAME"

        }

      ]

    },
    
    {

      "intent": "RemovePerson",

      "slots": [

        {

          "name": "Person",

          "type": "AMAZON.US_FIRST_NAME"

        }

      ]

    },
    
    {
      
      "intent": "SetPrice",

      "slots": [

        {

          "name": "Money",

          "type": "AMAZON.NUMBER"

        }

      ]

    },

    {

      "intent": "WhatsRanking"

    },
    
    {

      "intent": "ResetJar"

    },
    
    {

      "intent": "HowMuchInJar"

    },

    {

      "intent": "AMAZON.HelpIntent"

    }

  ]

}
