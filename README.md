# sample


	 withdraw();
    	 }
    	 
    	 
    	 System.out.println("Enter the Amount you want to withdraw");
    	  withdraw = sc.nextDouble();
    	  if(withdraw>currentBalance) {
    		  System.out.println("Yur Accounct Balance is low\n Reamining Balance:" +currentBalance);
    	  }
    	  
    	  else {
    	  currentBalance = currentBalance-withdraw;
    	   System.out.println("Amount Withdraw Successfully");
    	 System.out.println("Your Updated balance is :" +currentBalance);
    	  }
  }
     
     void checkBalance() {
    	 System.out.println("Your Current Account Balance is :" +currentBalance);
     }
