#Problem Statement

    *Purpose
    
      -To Streamline operations in the dairy industry ensuring collaboration of all stake holders.
      
      -The proposed platform  aims to ensure farmers get the value of investment made.
      
      
      
      
      
    *Problem definition
    
    
      -Farmer who experiences challenges in making profits on investment done in dairy farming
      
      -Farmer  gets connected to vet service provides and farm input providers
      
      -Farmers are registered by cooperatives and they will have a direct access to financial instituitions,the milk market and other key stakeholders int the dairy sector.
      
      -Farmer will have access to better  tools and information to improve production.  
      
      
      
      
      

    *Users
      -Farmer
          -characteristics
             -Speak English and Kiswahili
             -not necessary tech savvy
             -Have delivery arrangement
             -passionate about  their products
             -They take orders
             -They love feedback
             -They have preferred feeding products and routines
             -Curious learners

         -challenges they face
             -Poor storage facilities
             -Poor record keepings
             -Delayed Payments
             -Lack of enough inputs
             -Lack of capital
             -Managing orders
             -Transportation constraints
             -Lack of economies of scale in farming terms and information and how to combat disease.
             -Lack market for their products
      -Cooperative
          -Characteristics
             -Multilingual
             -tech savvies
             -have milk storage tanks
             -Have Capacity to help stakeholders to achieve goals.
             -Have employees
             -They can reach small scale and large scale farmers
             -Set and enforce  milk quality standards
             -Have rules and regulations.
             -offer open membership.
             -love feedback

         -challenges they face
             -Difficulty coordinating services among stakeholders
             -Do not have sufficient storage capacity 
             -Lack skill and vision to meet the growing demand of members.
             -Lack structured benefit packages to sustain farmers and keep them motivated
             -Keeping records
             -Lack of business relationship with buyers and suppliers
             -Tracking challenges
             -Corruption
      -Farm input Providers
         -characteristics
            -They store bulk amount of  inputs
            -Play a crucial role in  production
            -Distribute animal feeds
            -Their goods have inelastic demand
            -Love feedback
         
         -challenges they face
             -Fluctuating market
             -Transportation
             -difficult to control both quantity and quality  of output

      -Purchasers
          -characteristics
              -Tech savvies
              -multilingual
              -Expect fresh quality milk
              -Purchase milk at affordable prices
              -Expect milk deliveries on time
              -Order milk

         -challenges they face
             -Higher prices  due to inteferences by middlemen and inflation
             -Inadeqaute supply
             -Low quality 
             

      -Transpoters
         -characteristics
            -Offer delivery services on order
            -Tech savvies
            -multilingual
            -love feedback
         
         -challenges
            -They dont have designated delivery routes
            -Not designed for long distance
            -Accidents 
            -fuel  costs
            -Lack of cooling technologies when transporting
            -Forgetfulness
            -Poor delivery records management
            -Corruption 
            

      -Vet service providers
        -characteristics
            -Interact with farmers regardles of scale
            -Compassionate
            -Problem solver
            -Have extensive knowledge on agriculture
            -Multilingual
            -tech savvies
            -Love feedback
            -Go on order
            -have drugs
            -Offer breeding services $ AI
            
        -challenges
            -Communication
            -Learning new treatments and care
            -Transport
            -keeping track of vaccinating dates
            -Pricing and expenditures
            -Marketing
      -vet officers
        -characteristics
            -Interact with farmers regardles of scale
            -Compassionate
            -Problem solver
            -Have extensive knowledge on agriculture
            -Multilingual
            -tech savvies
            -Love feedback
            -Go on order
            -have drugs
            -Offer breeding services $ AI
        -challenges
            -Communication
            -Learning new treatments and care
            -Transport
            -keeping track of vaccinating dates
            -Pricing and expenditures
            -Marketing
           
            
      -Financial Instituitions
         -Characteristics
             -Offer credit to farmers for farm input
             -Help in expanding bst
             -Receive and dispatch various payments
             -Love feedback
             -multilingual
             -Tech savvies
         -Challenges
             -Defaulters
             -Too bossy
             

      
    *Scope
        -Product scope
            -The proposed platform will provide a one stop center through which these stakeholders collaborate for
             the purposes of ensuring that the farmer gets value for the investment made in dairy farming.
             The
             solution will be made available through App, web and USSD. 
             
    *Document Conventions
    

#Overall  Description
   *General System Requirements
         
      -Overall Perspective
            -Nortbound actors people to connect to
                 -Farmer-user
                 -Cooperatives-user
            -System -solution
                -blackbox-break into parts during thehigh level&low level design..
            -Southbound actors-systems to connect to
                -SMS Gateway-api for sending SMS
                -Email Server- Sending email messages
                -Payment Gateway-Financial
                -Authentication servers
                -Geo-location API-routes

                     
                        
          https://natujengecommunity.slack.com/files/U045J1G8X6U/F047P1SG49H/dairy_management_context_diagram.png       

                 
                
   *System features
        
   *Functional Requirements
     -Farmers
     
        -Farmer should be able to login
       
        -Farmer can update details(Password,mpesa number,bank details,)
        
        -Farmer  can transfer from one coopertaive to another
        
        -Farmer can access information from the cooperative(change in milk price(kg),input providers available,vet officers active)
        
        -Farmer is provided mechanism to have  self service functionalities
        
             -Check milk delivery reports
             
             -Payment Status for previous month deliveries
             
             -Review monthly milk sales
             
             -update delivery routes based on his/her location.
             
        -Farmer can receive feedback


      -Cooperatives
          -register farmers,update records 
          -create payment reports and initiate payment(farmers,transporters)
          -register vet officers, vet service providers,farm input providers,transporters,purchasers
          -Assign and update routes to transporters
          -Track deliveries(frequency)
          -Check status of the transporter,purchaser,vet officers and vet service providers
          -Product coding
                -Farm input products
                -Vet Products
          -Stock management
          -Capture milk delivery details and  delivery mode
          -Generate delivery statements for every farmer
          -Mantain and update delivery cycles
          -Determine total amount of money received by the cooperative at any given time
          -update delivery routes based on farmers location.
          
     -Transporter

          -Log in  to the system
          -Check routes
          -check delivery history
          -check payment status for current for previous periods
          -check specific farmer details
          -mark delivery as complete
          -check farmers assigned
          
   *Non-Functional Requirements
          -Should have a web portal for different entities  supporting the dairy ecosystem

#Interfaces
   *External Interface Requirements
       -User Interfaces
         -Web:
           -Both farmers and cooperatives will interact on web
         -SMS:
           -notifications
         -app
           -Farmers,transporters and cooperatives will interact using the app
         

       -Hardware Interfaces
        -None
       -Software Interfaces
          -SMS  gateway
             -HTTP API
          -Email server
             -SMTP interface
          -Authentication servers
              -Google
          -Payment gateway
              -Bank
              -Mpesa
          -Geo-location API
             -HTTP API
       -Communication Interfaces
          -None
   






#Model Analysis
      *Model Objects
          -Farmer
             -Document ID (National ID or Passport)
             - Document number (ID or passport number)
             -Registration Number
             -First Name
             -Middle Name
             -Last Name
             -Mobile number
             -Bank Name
             -Account number
             -Branch Name
             -County
             -Sub County
             -Total number of cows
             -No of lactating cows
             -Expected production per day (KG)
             -Transporter ID where transport is provided
             -Route ID
             -Transport type (self or through the transporters)
             -Ward
             -Village

          -Cooperative
             - Code
             -Registration certificate number
             -Cooperative name
             -County
             -Sub County
             - Ward
             - Contact Person
             -Contact number
             -Email address
          -Purchasers
             - Purchaser code
             -Identity type (National ID, Passport, Registration number, Certificate of incorporation
             -Identity number
             -Purchaser name
             -Contact Name
             -Contact number
             -Contact email address
             -Postal code
             -Postal Address
             -Town
             -Physical address
             -Delivery frequency (Daily, day of the week)
             -Expected quantity per delivery
          -transporters
            -Transporter ID
            -Transporter National ID
            -Transporter Name
            -Vehicle Registration number
            -Contact Name
            -Contact Number
            -Bank Name
            -Branch Name
            -Account Number
          -Vet service providers
            -Vet Provider ID
            -Identity type (National ID, Business registration certificate, Certificate of incorporation)
            -Identity name
            -Contact Name
            -Contact Mobile Number
            -Bank Name
            -Branch Name
            -Account Number
          -Vet officer
            - Vet Officer ID
            -National ID Number
            -Identity name
            -Contact Name
            -Contact Mobile Number
            -Bank Name
            -Branch Name
            - Account Number
          -Farm input provider
            -Input provider ID
            -Identity type (National ID, Business registration certificate, Certificate of incorporation)
            -Identity name
            -Contact Name
            -Contact Mobile Number
            -Bank Name
            -Branch Name
            -Account Number
          -Products
            -Product Type (Farm input or Vet)
            -Product ID
            -Product Name
            -Description
            -Unit of measure (KG, Litre, ml etc)
          -Notifications
          -Payment method
          -Milk reports
          -Feedback
          -Location
          -Deliveries


      *High level design
          -Components of dairy management system
              -Application(Mobile,web)
                    -Interfaces
                    -Funtions
              -APIs
                    -Functions
                       -Should be able to connect to the auth server.
                       -Perform CRUD operations,filter and search for all the model objects.
                       
                    -Inbound
                       -All CRUD APIs should  be consumed by the web app and Mobile app

                    -Outbound
                       -Able to send email notifications,
                       -send SMS notifications
                       -send auth request to the external auth services.
                       -view location
              -Database-MYSQL
                    -Functions
                        -Store model data
                    -Interfaces
                        -DB interfaces - JDBC in Java.
              -Notification service
                   - Function:
                         -connect to SMS gateway for sending of sms
                         -connect to Email server for sending email
                         -expose apis to send notification
                    -Interfaces:

                        -Inbound:

                            -send notification api
                        -Outbound:

                             -send sms api - to the SMS Gateway
                             -send email api - to email/SMTP server
              -Payment service
                    -Function
                          -receive a payment request from other modules and forward it to the payment gateway
                          -receive payment notification from the payment gateway and forward it to the inner modules
                    -interfaces
                          -inbound
                              -payment
                          -outbound
                              -payment request-payment gateway

              -Batch service
                  -Report generation
              
      *User experience 
          





