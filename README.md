![header](https://capsule-render.vercel.app/api?type=venom&color=auto&height=300&section=header&text=WOOD%20BREEZE&fontSize=90)
<hr>
<h3>:calendar: 1차 개발 기간 : 2024.02.16 ~ 2024.03.15 </h3>
<h3>:calendar: 2차 개발 기간 : 2024.03.20 ~ 진행중 </h3>
<h3>:hamster: 팀원소개 </h3>

|임가람|김태현|박수아|
|------|---|---|
|![캡처](https://github.com/river009/WOODBREEZE/assets/155034953/1eed7307-76c6-4647-9847-17ddcaf304d2)|![2](https://github.com/river009/WOODBREEZE/assets/155034953/41d824c3-e9fc-48bf-ae53-d242307f471c)|![3](https://github.com/river009/WOODBREEZE/assets/155034953/899ab1bb-a8ba-4d41-a6f4-d3c5c7b76194)|

<hr>
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
