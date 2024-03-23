![header](https://capsule-render.vercel.app/api?type=venom&color=auto&height=300&section=header&text=WOOD%20BREEZE&fontSize=90)
<hr>
<h3>:calendar: 1차 개발 기간 : 2024.02.16 ~ 2024.03.15 </h3>
<h3>:calendar: 2차 개발 기간 : 2024.03.26 ~ 진행중    </h3>
<h3>:hamster: 팀원소개 </h3>

|임가람|김태현|박수아|
|------|---|---|
|![KakaoTalk_20240323_172927244](https://github.com/river009/WOODBREEZE/assets/155034953/f5492ffd-d365-479b-8f99-56800d5e9e18)|![스크린샷 2024-03-23 173558](https://github.com/river009/WOODBREEZE/assets/155034953/37c1096b-206c-435f-96dc-b3865c8534a1)|![스크린샷 2024-03-23 172159](https://github.com/river009/WOODBREEZE/assets/155034953/2a63778e-d185-435c-931e-12f869e2322b)|

<hr>

<h2>:triangular_flag_on_post:프로젝트 소개</h2>
 프로젝트 이름 : WOOD BREEZE  
 
 프로젝트 목적 : 생산 lot 추적 플랫폼 구축 

<h3> 1) 테이블 설계도</h3>  
<details>
    <summary>설계도 펼치기</summary>
 
![woodbreeze](https://github.com/river009/WOODBREEZE/assets/155034953/a30f2e13-e1d1-40a2-8d82-d6ad71f72da0)

</details>
<h3> 2) 화면구성 </h3>  


<h2>:books:기술스텍</h2>

<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">  

<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white"> <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">


<h2>:sparkles:기능 설명</h2>

<H2>:file_folder:폴더구조</H2>  

<details>
    <summary>자세히</summary>

<!-- summary 아래 한칸 공백 두고 내용 삽입 -->

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

</details>
