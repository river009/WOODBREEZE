![header](https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=WOOD%20BREEZE&fontSize=90)

<H1>폴더구조</H1>  

📦src  
 ┣ 📂main  
 ┃ ┣ 📂generated    
 ┃ ┣ 📂java  
 ┃ ┃ ┗ 📂woodbreeze  
 ┃ ┃ ┃ ┗ 📂wdb  
 ┃ ┃ ┃ ┃ ┣ 📂controller  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ControlController.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ErrorController.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜IndexController.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜InspectionController.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LoginController.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LoginForm.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LotController.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜MemberController.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜MemberForm.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜OrderController.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜OrderForm.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ProcessController.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ProductController.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ProductForm.java  
 ┃ ┃ ┃ ┃ ┃ ┗ 📜SessionConst.java  
 ┃ ┃ ┃ ┃ ┣ 📂domain  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜CompanyName.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜Control.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ControlStatus.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜Error.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ErrorType.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜Grade.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜Inspection.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜InspectionStatus.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜Lot.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜MaterialName.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜Member.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜Orders.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜OrderStatus.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜Process.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ProcessName.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜Product.java  
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ProductName.java  
 ┃ ┃ ┃ ┃ ┣ 📂exception  
 ┃ ┃ ┃ ┃ ┃ ┗ 📜NotEnoughStockException.java  
 ┃ ┃ ┃ ┃ ┣ 📂repository    
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ControlRepository.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ControlStatusRepository.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ErrorRepository.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜InspectionRepository.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LotRepository.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜MemberRepository.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜OrderRepository.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ProcessRepository.java   
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ProductRepository.java    
 ┃ ┃ ┃ ┃ ┣ 📂service  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ControlService.java  
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ControlStatusService.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ErrorService.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜InspectionService.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LoginService.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LotService.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜MemberService.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜OrderScheduler.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜OrderService.java   
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ProcessService.java   
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ProductService.java   
 ┃ ┃ ┃ ┃ ┣ 📜DummyDataLoader.java    
 ┃ ┃ ┃ ┃ ┣ 📜SchedulerApplication.java    
 ┃ ┃ ┃ ┃ ┗ 📜WdbApplication.java    
 ┃ ┗ 📂resources    
 ┃ ┃ ┣ 📂static   
 ┃ ┃ ┃ ┣ 📂css   
 ┃ ┃ ┃ ┃ ┣ 📜bootstrap.css   
 ┃ ┃ ┃ ┃ ┣ 📜index.css    
 ┃ ┃ ┃ ┃ ┣ 📜jumbotron-narrow.css   
 ┃ ┃ ┃ ┃ ┗ 📜style.css   
 ┃ ┃ ┃ ┣ 📂font   
 ┃ ┃ ┃ ┣ 📂image  
 ┃ ┃ ┃ ┗ 📂js   
 ┃ ┃ ┃ ┃ ┣ 📂package   
 ┃ ┃ ┃ ┃ ┃ ┣ 📂auto    
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜auto.cjs  
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜auto.d.ts   
 ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜auto.js   
 ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜package.json    
 ┃ ┃ ┃ ┃ ┗ 📜bootstrap.bundle.min.js  
 ┃ ┃ ┣ 📂templates  
 ┃ ┃ ┃ ┣ 📂control  
 ┃ ┃ ┃ ┃ ┗ 📜processControl.html   
 ┃ ┃ ┃ ┣ 📂fragments  
 ┃ ┃ ┃ ┃ ┣ 📜bodyHeader.html   
 ┃ ┃ ┃ ┃ ┣ 📜bodyHeader2.html  
 ┃ ┃ ┃ ┃ ┣ 📜footer.html   
 ┃ ┃ ┃ ┃ ┗ 📜header.html   
 ┃ ┃ ┃ ┣ 📂login      
 ┃ ┃ ┃ ┃ ┗ 📜loginForm.html    
 ┃ ┃ ┃ ┣ 📂members   
 ┃ ┃ ┃ ┃ ┣ 📜createMember.html   
 ┃ ┃ ┃ ┃ ┣ 📜memberList.html   
 ┃ ┃ ┃ ┃ ┗ 📜updateMember.html  
 ┃ ┃ ┃ ┣ 📂orders   
 ┃ ┃ ┃ ┃ ┣ 📜orderForm.html   
 ┃ ┃ ┃ ┃ ┣ 📜orderList.html   
 ┃ ┃ ┃ ┃ ┗ 📜orderList1.html   
 ┃ ┃ ┃ ┣ 📂process   
 ┃ ┃ ┃ ┃ ┣ 📜processList.html   
 ┃ ┃ ┃ ┃ ┣ 📜processList1.html   
 ┃ ┃ ┃ ┃ ┗ 📜processSet.html  
 ┃ ┃ ┃ ┣ 📂product   
 ┃ ┃ ┃ ┃ ┣ 📜createProductForm.html  
 ┃ ┃ ┃ ┃ ┣ 📜detailedList.html   
 ┃ ┃ ┃ ┃ ┣ 📜detailedList1.html   
 ┃ ┃ ┃ ┃ ┣ 📜ProductList.html   
 ┃ ┃ ┃ ┃ ┣ 📜ProductList1.html   
 ┃ ┃ ┃ ┃ ┗ 📜updateProductForm.html  
 ┃ ┃ ┗ 📜application.yml  
