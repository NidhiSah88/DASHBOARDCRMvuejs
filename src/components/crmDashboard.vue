<template>
  <!-- <div class=""> -->
     <div class="side-menu">
        <div class="brand-name">
            <h1 class="mang">CRM.io</h1>
        </div>
        <div>
          <!-- <button class="dasboard" type="button"> Dashboard </button> -->
           <button class="rounded-buttonD">
            <!-- <img class="icon" src="../assets/das.png" alt=""> -->
            Dashboard  </button>
        </div>

        <ul>
          <h2 class="mang"> Management </h2>
            <li><img class="icon" src="../assets/document.png" alt="">&nbsp; <span>Document</span> </li>
            <li><img class="icon" src="../assets/contact.png" alt="">&nbsp;<span>Contact</span> </li>
            <li><img class="icon" src="../assets/contact.png" alt="">&nbsp;<span>Prospect</span> </li>
            <li><img class="icon" src="../assets/workflow.png" alt="">&nbsp;<span>Workflow</span> </li>
            
        </ul>
        <div class="hrline"> </div>
          

          <ul>
          <h2 class="mang" > Connection </h2>
             <li><img class="icon" src="../assets/workflow.png" alt="">&nbsp;<span>Chat Integration </span> </li>
            <li><img class="icon" src="../assets/workflow.png" alt="">&nbsp; <span>Marketing </span></li>
            <li><img class="icon" src="../assets/workflow.png" alt="">&nbsp;<span>Email Integration</span> </li>
        
          </ul>
        <div class="hrline"> </div>


           <ul>
          <h2 class="mang" > Customer </h2>
             <li><img class="icon" src="../assets/workflow.png" alt="">&nbsp;<span>Transaction</span> </li>
            <li><img class="icon" src="../assets/workflow.png" alt="">&nbsp; <span>Maintenance</span></li>
        
          </ul>
    </div>
    <div class="container">
        <div class="header">
            <div class="nav">
                <div class="search">
                  Overview
                  </div>
                <div class="user">
                    <img class="noti" src="../assets/notification.jpg" alt="">
                    <div class="img-case">
                        <img class="profile"  src="../assets/profile.png" alt="">
                    </div>
                    <a href="#" class="admin">Administrator</a>
                        <img class="downarrow"  src="../assets/downarrow.png" alt="">

                </div>
            </div>
        </div>
        <div class="content">
            <div class="content-2 chatcol">
                   <div class="new-students">
                    <div class="title1">
                        <h2>Popular Product</h2>
                    </div>
                    <table>
                        <tr>
                            <th> </th>
                            <th> </th>
                        </tr>
                        <tr>
                            <td> 
                                <!-- <img src="user.png" alt=""> -->
                                 <img class="producticon"  src="../assets/profile.png" alt="">
                            </td>

                            <td>John Steve Doe
                                <h5>$250 </h5>
                            </td>
                        </tr>
                        <tr>
                            <td> <img class="producticon"  src="../assets/profile.png" alt="">  </td>
                            <td>John Steve Doe 
                                 <h5 >$50 </h5>
                            </td>
                            <!-- <td><img src="info.png" alt=""></td> -->
                        </tr>
                        <tr>
                            <td> <img class="producticon"  src="../assets/profile.png" alt=""> </td>
                            <td>John Steve Doe
                                 <h5 >$100 </h5>
                            </td>
                        </tr>
                        <tr>
                            <td> <img class="producticon"  src="../assets/profile.png" alt=""> </td>
                            <td>John Steve Doe
                                 <h5 >$2500 </h5>
                            </td>
                        </tr>

                    </table>
                    <!-- <hr/> -->
                     <div class="title1">
                        <h2>Chat</h2>
                    </div>
                    <table>
                        <tr>
                            <th></th>
                            <th></th>
                        </tr>
                        <tr>
                            <td> 
                                <!-- <img src="user.png" alt=""> -->
                                 <img class="producticon"  src="../assets/profile.png" alt="">
                            </td>

                            <td>John Steve Doe
                                 <h5 > How many product? </h5>
                            </td>
                        </tr>
                        <tr>
                            <td> <img class="producticon"  src="../assets/profile.png" alt="">  </td>
                            <td>John Steve Doe  <h5 > How many meeting </h5></td>
                            <!-- <td><img src="info.png" alt=""></td> -->
                        </tr>
                        <tr>
                            <td> <img class="producticon"  src="../assets/profile.png" alt=""> </td>
                            <td>John Steve Doe  <h5 > How many product? </h5></td>
                        </tr>
                        <tr>
                            <td> <img class="producticon"  src="../assets/profile.png" alt=""> </td>
                            <td>John Steve Doe  <h5 > How many product? </h5> </td>
                        </tr>

                    </table>
                </div>

            </div>
            <div class="cards">
                <div class="card">
                     
                    <div class="box">
                        <p class="doccontent">Document</p>

                        <h1>146.000</h1>
                        <h5 >17 % Since last week</h5>
                    </div>
                    <div class="icon-case">
                        <img class="boxicon"  src="../assets/document.png" alt="">

                    </div>
                </div>
                 <div class="card">
                     
                    <div class="box">
                        <p class="doccontent">Contact</p>

                        <h1>1400</h1>
                        <h5 >17 % Since last week</h5>
                    </div>
                    <div class="icon-case">
                        <!-- <img src="students.png" alt=""> -->
                        <img class="boxicon"  src="../assets/contact.png" alt="">

                    </div>
                </div>
                 <div class="card">
                    
                    <div class="box">
                        <p class="doccontent">Email</p>

                        <h1>150.000</h1>
                        <h5 >17 % Since last week</h5>
                    </div>
                    <div class="icon-case">
                        <img class="boxicon"  src="../assets/email.jpeg" alt="">

                    </div>
                </div>
               
            </div>
             <div class=" largecards ">
                <div class="card largebox">
                    
                    <div class="box">
                        <p class="doccontent">Recent Workflow</p>

                        <h3 >17 % </h3>
                    </div>
                    <div class="icon-case">
                        <!-- <img src="students.png" alt=""> -->
                        <img class="workicon"  src="../assets/linechart.png" alt="">
                    </div>
                     <!-- <LineChart /> -->
                </div>
                 <div class="card largebox">
                    
                    <div class="box">
                        <p class="doccontent">Recent Marketing</p>

                        <h3 >17 % </h3>
                    </div>
                    <div class="icon-case">
                        <img class="workicon"  src="../assets/barchart.png" alt="">

                    </div>
                </div>
                 
            </div>
            <div class="content-2">
                <div class="recent-payments">
                    <div class="title">
                        <h2>Document</h2>
                         <button class="rounded-buttonW">Weekly  
                        <img class="downarrow"  src="../assets/downarrow.png" alt="">
                        </button>

                    </div>
                    <h5 class="prod"> How many product? </h5>
                    <table>
                        <tr>
                            <th>Name</th>
                            <th>File</th>
                            <th>Category</th>
                            <th>Author</th>
                            <th>Status</th>

                        </tr>
                        <tr>
                            <td>John Doe</td>
                            <td>St. James College</td>
                            <td>$120</td>
                            <td>John Doe</td>
                             <td>
                                 <button class="rounded-button">Send</button>                                
                            </td>
                            <!-- <td><a href="#" class="btn">Sent</a></td> -->
                        </tr>
                        <tr>
                            <td>John Doe</td>
                            <td>St. James College</td>
                            <td>$120</td>
                            <td>John Doe</td>
                            <td>
                                 <button class="rounded-button">Send</button>                                
                            </td>
                        </tr>
                        <tr>
                            <td>John Doe</td>
                            <td>St. James College</td>
                            <td>$120</td>
                            <td>John Doe</td>
                            <td>
                                 <button class="rounded-buttonP">Pending</button>                                
                            </td>
                            <!-- <td><a href="#" class="btn">Pending</a></td> -->
                        </tr>
                      
                    </table>
                </div>
                 
             
            </div>
            
        </div>
        <!-- <div class="content-right"> -->
            
        <!-- </div> -->
         
    </div>
   
   
    
  <!-- </div> -->
</template>

<script setup>

// import LineChart from './LineChart.vue';


</script>

<style scoped>
.overv{
    font-weight: bold;
}
canvas {
  width: 100%;
  height: 400px;
}
.prod{
    display: flex;
    margin-top: 0px;
    margin-left: 10px;
    margin-bottom: 7px;
}
.rounded-buttonD {

  padding: 0 20px;
  border-radius: 5px;
  border: none; 
margin-right: 90px;
   font-weight: bold;
  font-size: 16px; 
  cursor: pointer; 
  /* display: flex; */
  justify-content: center;
  align-items: center;
  text-align: center;

  border-radius: 5px;
    width: 140px;
    height: 40px;
    color: white;
    margin-top: 20px;
    margin-bottom: 20px;
  background-color: #0c67e1;


}

.rounded-button {
  height: 30px;
  width: 80px;
  padding: 0 20px;
  border-radius: 5px;
  border: none; 
  background-color: #62db5e;
  opacity: 0.5;
  color: rgb(11, 72, 11); 
  font-weight: bold;
  font-size: 16px; 
  cursor: pointer; 
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  transition: background-color 0.3s;

}

.rounded-buttonP {
  height: 30px;
  width: 80px;
  padding: 0 20px;
  border-radius: 5px;
  border: none; 
  background-color: #df4b16;
  opacity: 0.5;
  font-weight: bold;
  color: rgb(123, 25, 3); 
  font-size: 16px; 
  cursor: pointer; 
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  transition: background-color 0.3s;

}
.rounded-buttonW {
  height: 30px;
  width: 80px;
  padding: 0 20px;
  border-radius: 5px;
  border: none; 
  background-color: #f1f1f1;
  opacity: 0.5;
  font-weight: bold;
  color: black; 
  font-size: 16px; 
  cursor: pointer; 
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  transition: background-color 0.3s;

}
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}
body {
    min-height: 100vh;
}
a {
    text-decoration: none;
}
li {
    list-style: none;
}
h1,
h2 {
    color: #444;
        margin-right: 70px;

}
h3 {
    color: #999;
    margin-top: 10px;
    font-size: 15px;
}
h5 {
    color: #999;
    margin-top: 10px;
    font-size: 15px;
}
.dasboard{
    border-radius: 5px;
    width: 140px;
    height: 40px;
    background: #4040FF;
    color: white;
    margin-top: 20px;
    margin-bottom: 20px;
}
.doccontent{
     display: flex;
  align-items: center;
  margin-block: 20px;
  font-weight:bold;
}
.button {
  background-color: #54f070; /* Green */
  opacity: 0.7;
  border: none;
  color: white;
  padding: 20px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}
.button3 {border-radius: 8px;}



.boxicon{
    height: 25px !important;
    width: 25px !important;
    margin-bottom: 60px;

}
.producticon{
     height: 25px !important;
    width: 25px !important;
}
.largebox{
    width: 400px !important;
    height: 200px !important;
     background: white;
    margin: 20px 10px;
    display: flex;
    align-items: center;
    justify-content: space-around;
    border-radius: 10px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
.workicon{
    height: 100px !important;
    width: 100% !important;
}
.largecards{
        padding: 20px 15px;
    display: flex;
    align-items: center;
    /* justify-content: space-between; */
    flex-wrap: wrap;
    
    

}


.icon{
    width: 20px ;
    height: 20px;
}
.profile .noti .admin{
     width: 20px !important;
    height: 20px !important;
    margin-left: 20px;
}
.noti{
    width: 20px !important;
    height: 20px !important;
}
.downarrow{
    height: 15px !important;
    width: 15px !important;
}
.hrline{
    width: 80%;
    margin-left: 32px;
    margin-right: 40px;
    border-bottom: 2px solid #0c67e1;
    margin-top: 10px;
    margin-bottom: 10px;
    padding: 10px;
    /* padding: 10px 0px 10px 0px; */

}
.mang{
    color: #0c67e1;
}
.btn {
    background: #f05462;
    color: white;
    padding: 5px 10px;
    text-align: center;
}
.btn:hover {
    color: #f05462;
    background: white;
    padding: 3px 8px;
    border: 2px solid #f05462;
}
.title {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 15px 10px;
    /* border-bottom: 2px solid #999; */
}
.title1{
    display: flex;
    align-items: center;
    padding: 15px 10px;
}
table {
    padding: 10px;
}
th,
td {
    text-align: left;
    padding: 8px;
}
.side-menu {
   
    position: fixed;
    top: 0;
    background: #000040;
    width: 20vw;
    height: 100vh;
    display: flex;
    flex-direction: column;
}
.side-menu .brand-name {
    height: 10vh;
    display: flex;
    align-items: center;
    justify-content: center;
}
.side-menu li {
    font-size: 24px;
    padding: 10px 40px;
    color: white;
    display: flex;
    align-items: center;
}
.side-menu li:hover {
    background: white;
    color: #0c67e1;
}
.container {
    position: absolute;
    right: 0;
    width: 80vw;
    height: 100vh;
    background: #f1f1f1;
}
.container .header {
    position: fixed;
    top: 0;
    right: 0;
    width: 80vw;
        height: 13vh;
    background: #f1f1f1;
    display: flex;
    align-items: center;
    justify-content: center;
    /* box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); */
    z-index: 1;
}
.container .header .nav {
    width: 90%;
    display: flex;
    align-items: center;
}
.container .header .nav .search {
    flex: 3;
    display: flex;
    font-weight: bold;
}
.container .header .nav .search input[type=text] {
    border: none;
    background: #f1f1f1;
    padding: 10px;
    width: 50%;
}
.container .header .nav .search button {
    width: 40px;
    height: 40px;
    border: none;
    display: flex;
    align-items: center;
    justify-content: center;
}
.container .header .nav .search button img {
    width: 30px;
    height: 30px;
}
.container .header .nav .user {
    flex: 1;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.container .header .nav .user img {
    width: 40px;
    height: 40px;
}
.container .header .nav .user .img-case {
    position: relative;
    width: 50px;
    height: 50px;
}
.container .header .nav .user .img-case img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
.container .content {
    position: relative;
    margin-top: 10vh;
    min-height: 90vh;
    background: #f1f1f1;
}
.container .content .cards {
    padding: 20px 15px;
    display: flex;
    align-items: center;
    /* justify-content: space-between; */
    flex-wrap: wrap;
}
.container .content .cards .card {
    width: 250px;
    height: 150px;
    background: white;
    margin: 20px 10px;
    display: flex;
    align-items: center;
    justify-content: space-around;
    border-radius: 10px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
.chatcol{
    
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    float: right;
        margin-top: 40px;
}
.container .content .content-2 {
    min-height: 60vh;
    display: flex;
    justify-content: space-around;
    align-items: flex-start;
    flex-wrap: wrap;
}
.container .content .content-2 .recent-payments {
    min-height: 50vh;
    flex: 5;
    background: white;
    margin: 0 25px 25px 25px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    display: flex;
    flex-direction: column;
}
.container .content .content-2 .new-students {
    flex: 2;
    background: white;
    min-height: 50vh;
    margin: 0 25px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    display: flex;
    flex-direction: column;
}
.container .content .content-2 .new-students table td:nth-child(1) img {
    height: 40px;
    width: 40px;
}
@media screen and (max-width: 1050px) {
    .side-menu li {
        font-size: 18px;
    }
}
@media screen and (max-width: 940px) {
    .side-menu li span {
        display: none;
    }
    .side-menu {
        align-items: center;
    }
    .side-menu li img {
        width: 40px;
        height: 40px;
    }
    .side-menu li:hover {
        background: #0c67e1;
        padding: 8px 38px;
        border: 2px solid white;
    }
}
@media screen and (max-width:536px) {
    .brand-name h1 {
        font-size: 16px;
    }
    .container .content .cards {
        justify-content: center;
    }
    .side-menu li img {
        width: 30px;
        height: 30px;
    }
    .container .content .content-2 .recent-payments table th:nth-child(2),
    .container .content .content-2 .recent-payments table td:nth-child(2) {
        display: none;
    }
}
</style>
