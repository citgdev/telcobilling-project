# One Telco Billing Project

transfer Telco Billing to One System 

The DB is located sa 192.168.10.251\MSSQL_2016 
naka json format gehapun ang pagpasa og Data to DB


For UI Theme lets use the Old Telco Billing UI Theme

OLD Telco Billing Dev 
http://192.168.10.251:8097/
Username : GaringArmando
Password : Default@123


Ang new DB SA 192.168.10.251\MSSQL_2016
DB NAME : ONE_TELCO_BILLING

Function para Maka Connect sa SQL 
LoginTELCO()

# NOTES ;
Use camel case for naming of functions ( JS , controller, Model ) 
  Example : getProfiles() 
  
Format on Naming a function, starts with action word then Noun
  Exampl get <= actionWord , Profiles <= Noun [ getProfiles() ]

New Way of declaring functions 
  // OLD WAY 
  functionName : function(parameters) { 
     // do something
  }
  
  // New Way Use Arrow Functions 
   functionName : ( param1, param2 ) => { 
     // do something
   }
   
  // Arrow Functions with 1 parameter 
   functionName : param => { 
     // do something
   }
   
  // Arrow Functions without parameter 
  functionName : () => { 
     // do something
   }

 fetching attributes/value
 
 // Old Way 
  $(this).attr('data-something') / $(this).val()
// New Way 
  $(e.currentTarget).attr('data-something') / ( e.currentTarget).val()

HTML Element Naming reference
	* textarea 	= txt-description
	* input	  	= in-firstname
	* radio	  	= rd-gender
	* select    	= sel-isstatus
	* button   	= btn-save-transaction
        * form      	= frm-login
	* table	  	= tbl-item
	* div        	= dv-holder-item
	* array     	= arr-item





 
   
