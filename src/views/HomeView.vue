<template>
  <div class="container-fluid page-body bg-light">

<div class="row">

  

  <div class="col-md-12  bg-secondary">
    <div class="fixed-top">
    
<nav class="navbar navbar-expand-lg navbar-light bg-light">
 
    <!-- Navbar brand -->
     <img class="navbar-brand logo mx-3" src="/assets/images/zhivago-logo.png" alt="logo" />

    <!-- Toggle button -->
    <button class="navbar-toggler" type="button">
      <i class="fas fa-bars" onclick="toggleSideNav()"></i>
    </button>

    <!-- Collapsible wrapper -->
    <div class="collapse navbar-collapse" id="navbarButtonsExample">
       <form style="margin-left:34px">
             <div class="search">
               <input class="nav-form-input form-control" type="text" placeholder="Search" aria-label="Search">
               <i class="mdi mdi-magnify icon"></i> 
             </div>
          </form>
      <div class="d-flex align-items-center px-5">
      <router-link to="/login">
        <button type="button" class="btn btn-success px-3 me-2">
          Login
        </button>
      </router-link>
      <router-link to="/register">
        <button type="button" class="btn btn-primary me-2">
          Sign up for free
        </button>
      </router-link>  
      </div>
    </div>
    <!-- Collapsible wrapper -->
  <!-- Container wrapper -->
</nav>
<!-- Navbar -->


   </div>
  </div>
 </div>

    <div class="row">
               
    <nav id="mySidenav" class="col-md-3 sidebar-left p-4 d-md-block bg-light">
      <div class="position-sticky pt-5">
        <ul class="nav flex-column  nav-pills list-unstyled">
          <li class="mb-3">
            <a class="nav-link active" aria-current="page" href="/login">
             <span class="mdi mdi-home nav-icon" ></span>
              Home
            </a>
            <a class="nav-link bg-light" aria-current="page" href="#">
              <span class="mdi mdi-account nav-icon" ></span>
              Members
            </a>
          </li>

      <li class="mb-1 nav-item nav-link bg-light">
        <a class="text-muted align-items-center rounded collapsed d-flex justify-content-between" data-bs-toggle="collapse" data-bs-target="#home-collapse" aria-expanded="true">
         Home
         <span class="mdi mdi-chevron-down" style="font-size:20px" ></span>
        </a>
        <div class="collapse show" id="home-collapse">
          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
             <li class="nav-item">
            <a class="nav-link bg-light" href="#">
             <span class="" >&#x1F354;</span>
              Customers
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link bg-light" href="#">
             <span class="" >&#x1F624;</span>
              Reports
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link bg-light" href="#">
              <span class="" >&#x1F594;</span>
              Integrations
            </a>
          </li>
        
          </ul>
        </div>
      </li>
      <li class="mb-1 nav-item nav-link bg-light">
        <a class="text-muted  align-items-center collapsed d-flex justify-content-between" data-bs-toggle="collapse" data-bs-target="#dashboard-collapse" aria-expanded="false">
          Dashboard
          <span class="mdi mdi-chevron-down" style="font-size:20px" ></span>
        </a>
        <div class="collapse" id="dashboard-collapse">
          <ul class="btn-toggle-nav list-unstyled fw-normal pb-1 small">
             <li class="nav-item">
            <a class="nav-link bg-light" href="#">
             <span class="" >&#x1F354;</span>
              Customers
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link bg-light" href="#">
             <span class="" >&#x1F624;</span>
              Reports
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link bg-light" href="#">
              <span class="" >&#x1F594;</span>
              Integrations
            </a>
          </li>
        
          </ul>
        </div>
      </li>


          <li class="nav-item bg-light">
            <a class="nav-link bg-light" href="#">
             <span class="" >&#x1F354;</span>
              Customers
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link bg-light" href="#">
             <span class="" >&#x1F624;</span>
              Reports
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link bg-light" href="#">
              <span class="" >&#x1F594;</span>
              Integrations
            </a>
          </li>
        </ul>

        <h6 class="sidebar-heading d-flex justify-content-between align-items-center px-3 mt-4 mb-1 text-muted">
          <span >Saved reports</span>
          <a class="link-secondary" href="#" aria-label="Add a new report">
           <span class="" >&#x2F354;</span>
          </a>
        </h6>
        <ul class="nav flex-column  nav-pills list-unstyled">
          <li class="nav-item">
            <a class="nav-link bg-light" href="#">
               <span class="" >&#x1F554;</span>
              Current month
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link bg-light" href="#">
            <span class="" >&#x1F353;</span>
              Last quarter
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link bg-light" href="#">
              <span class="" >&#x1F324;</span>
              Social engagement
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link bg-light" href="#">
               <span class="" >&#x1F351;</span>
              Year-end sale
            </a>
          </li>
           <li class="nav-item">
            <a class="nav-link bg-light" href="#">
            <span class="" >&#x1F353;</span>
              Last quarter
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link bg-light" href="#">
              <span class="" >&#x1F324;</span>
              Social engagement
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link bg-light" href="#">
               <span class="" >&#x1F351;</span>
              Year-end sale
            </a>
          </li>
           <li class="nav-item">
            <a class="nav-link bg-light" href="#">
            <span class="" >&#x1F353;</span>
              Last quarter
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link bg-light" href="#">
              <span class="" >&#x1F324;</span>
              Social engagement
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link bg-light" href="#">
               <span class="" >&#x1F351;</span>
              Year-end sale
            </a>
          </li>
        </ul>
      </div>
    </nav> 


   

 
    
  
  <nav id="sidebarMenu" class="col-md-3 sidebar-right p-4 d-md-block bg-light collapse">
      <div class="position-sticky pt-5">
       <ul class="nav flex-column mb-auto px-4 box-shadow" style="background:white;">
          <li class="nav-item">
            <p class="Trend-text px-1 mt-3 text-muted p-trending-post">Trending Posts</p>
                 <div class="preview-list">
                      <div class="preview-item">
                        <div class="preview-thumbnail">
                          <img src="/assets/images/faces/face1.jpg" alt="image" class="rounded-circle status" />
                          <div class="active"></div>
                        </div>
                        <div class="preview-item-content d-flex flex-grow">
                          <div class="flex-grow">
                            <div class="d-flex d-md-block d-xl-flex justify-content-between">
                              <h6 class="preview-subject p-user-name">Leonard</h6>
                            </div>
                            <p class="text-muted p-sidbar-text">Well, it seems to be working now.</p>
                          </div>
                        </div>
                      </div>
                 </div>
          </li>
          <li class="nav-item">
              <div class="preview-list">
                      <div class="preview-item">
                        <div class="preview-thumbnail">
                          <img src="/assets/images/faces/face2.jpg" alt="image" class="rounded-circle" />
                          <div class="active"></div>
                        </div>
                        <div class="preview-item-content d-flex flex-grow">
                          <div class="flex-grow">
                            <div class="d-flex d-md-block d-xl-flex justify-content-between">
                              <h6 class="preview-subject p-user-name">Leonard</h6>
                            </div>
                            <p class="text-muted p-sidbar-text">Well, it seems to be working now.</p>
                          </div>
                        </div>
                      </div>
                </div>
          </li>
         
          
          <li class="nav-item">
              <div class="preview-list">
                      <div class="preview-item">
                        <div class="preview-thumbnail">
                          <img src="/assets/images/faces/face3.jpg" alt="image" class="rounded-circle" />
                          <div class="active"></div>
                        </div>
                        <div class="preview-item-content d-flex flex-grow">
                          <div class="flex-grow">
                            <div class="d-flex d-md-block d-xl-flex justify-content-between">
                              <h6 class="preview-subject p-user-name">Leonard</h6>
                            </div>
                            <p class="text-muted p-sidbar-text">Well, it seems to be working now.</p>
                          </div>
                        </div>
                      </div>
                </div>
          </li>

          <li class="nav-item px-2">
            <p class="text-muted text-muted p-see-all">See all</p>
          </li>
        </ul>


          <ul class="nav flex-column mb-auto px-4 mt-3 box-shadow" style="background:gray;height:180px">
          <li class="nav-item p-0 m-0">
               
          </li>
        </ul>

        
      </div>
    </nav> 

 
  <div class="main-view col-md-6  container bg-light">
    <div class="row content gy-2">

      <div class="card card1 bg-light p-0 m-0  px-3">
        <div class="card-body bg-light p-0 m-0">
          <div class="d-flex flex-row justify-content-between mt-3">
            <h4 class="card-title">Home</h4>
            <!-- <ul class="ul-list mx-2 list-inline">
              <li class="list-inline-item"><p class="text-muted mb-1 small p-view-all p-1">Latest</p> </li>
              <li class="list-inline-item"><i class="mdi mdi-chevron-down ul-list-icon"></i></li>
            </ul> -->
            <div class="dropdown">
              <a
                class="dropdown-toggle text-muted"
                href="#"
                role="button"
                id="dropdownMenuLink"
                data-mdb-toggle="dropdown"
                aria-expanded="false"
              >
              Latest
              </a>

              <ul class="dropdown-menu" aria-labelledby="dropdownMenuLink">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li><a class="dropdown-item" href="#">Something else here</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>


      <div class="card   p-0 mt-2 mb-4">
        <div class="card-body m-0 p-0">
             <div class="d-flex justify-content-center">
                <img src="/cars/11231.jpg" class="img-fluid" alt="...">
             </div>
          </div>
      </div>

      <div class="card text-dark mb-2 box-shadow p-0 m-0">
            <div class="card-header  d-flex  d-xl-flex justify-content-between p-0 m-0 px-3">
                  <div class="preview-list">
                      <div class="preview-item">
                        <div class="preview-thumbnail">
                          <img src="/assets/images/faces/face6.jpg" alt="image" class="rounded-circle status" />
                          <div class="active"></div>
                        </div>
                        <div class="preview-item-content d-flex flex-grow">
                          <div class="flex-grow">
                            <div class="d-flex d-md-block d-xl-flex justify-content-between">
                              <h6 class="preview-subject p-user-name">Silas Udofia</h6>
                            </div>
                             <span class="badge rounded-pill bg-primary">Admin</span>
                             <span class="mx-1 badge rounded-pill bg-primary">now</span>
                            <p class="text-muted p-card-header mt-2">Well, it seems to be working now.</p>
                          </div>
                        </div>
                      </div>
                 </div>
                  <p class="text-muted mt-2 small p-share p-1">Share</p>
          </div>
          <div class="card-body m-0 p-0">
            <div class="mx-3">
               <p class="p-card-body">hello there</p>
            </div>
             <div class="d-flex justify-content-center py-1">
                <img src="/cars/11231.jpg" class="img-fluid" alt="...">
             </div>
          </div>
          <div class="card-footer mt-4 py-3 border-top" style="background-color:white; border:none">
               <div class="row row-footer">
                 <div class="col-4">
                    <div class="col-12 footer-div">
                      <i class="mdi mdi-thumb-up-outline"></i>
                      <p>7m</p>
                    </div>
                 </div>
                 <div class="col-4">
                     <div class="col-12 footer-div">
                      <i class="mdi mdi-message-outline"></i>
                      <p>12</p>
                     </div>
                 </div>
                 <div class="col-4">
                    <div class="col-12 footer-div">
                        <i class="mdi mdi-share-outline"></i>
                        <p class="">4</p>
                    </div>
                 </div>
               </div>
          </div>
       </div>


       <div class="card text-dark mt-3 box-shadow p-0 m-0">
            <div class="card-header  d-flex  d-xl-flex justify-content-between p-0 m-0 px-3">
                  <div class="preview-list">
                      <div class="preview-item">
                        <div class="preview-thumbnail">
                          <img src="/assets/images/faces/face6.jpg" alt="image" class="rounded-circle" />
                         <div class="active"></div>
                        </div>
                        <div class="preview-item-content d-flex flex-grow">
                          <div class="flex-grow">
                            <div class="d-flex d-md-block d-xl-flex justify-content-between">
                              <h6 class="preview-subject p-user-name">Silas Udofia</h6>
                            </div>
                            <span class="badge rounded-pill bg-primary">5 days ago</span>
                            <p class="text-muted p-card-header mt-2">Well, it seems to be working now.</p>
                          </div>
                        </div>
                      </div>
                 </div>
                  <p class="text-muted mt-2 small p-share p-1">Share</p>
          </div>
          <div class="card-body m-0 p-0">
             <div class="mx-3">
               <p class="p-card-body">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Necessitatibus tenetur ab odio adipisci nihil recusandae. Nobis fuga minus excepturi quae tenetur rem aperiam accusamus amet ex possimus? Consectetur, debitis corporis.</p>
             </div>
              <div class="d-flex justify-content-center py-1">
                 <img src="/cars/14444.jpg" class="img-fluid" alt="...">
              </div>
          </div>
          <div class="card-footer mt-4 py-3 border-top" style="background-color:white; border:none">
               <div class="row row-footer">
                  <div class="col-4">
                    <div class="col-12 footer-div">
                      <i class="mdi mdi-thumb-up-outline"></i>
                      <p>10k</p>
                    </div>
                 </div>
                 <div class="col-4">
                     <div class="col-12 footer-div">
                      <i class="mdi mdi-message-outline"></i>
                      <p>12</p>
                     </div>
                 </div>
                 <div class="col-4">
                    <div class="col-12 footer-div">
                        <i class="mdi mdi-share-outline"></i>
                        <p class="">4</p>
                    </div>
                 </div>
               </div>
          </div>
       </div>


<div class="card text-dark mt-4 box-shadow p-0 m-0">
            <div class="card-header  d-flex  d-xl-flex justify-content-between p-0 m-0 px-3">
                  <div class="preview-list">
                      <div class="preview-item">
                        <div class="preview-thumbnail">
                          <img src="/assets/images/faces/face6.jpg" alt="image" class="rounded-circle" />
                         <div class="active"></div>
                        </div>
                        <div class="preview-item-content d-flex flex-grow">
                          <div class="flex-grow">
                            <div class="d-flex d-md-block d-xl-flex justify-content-between">
                              <h6 class="preview-subject p-user-name">Silas Udofia</h6>
                            </div>
                            <span class="badge rounded-pill bg-primary">3 days ago</span>
                            <p class="text-muted p-card-header mt-2">Well, it seems to be working now.</p>
                          </div>
                        </div>
                      </div>
                 </div>
                  <p class="text-muted mt-2 small p-share p-1">Share</p>
          </div>
          <div class="card-body m-0 p-0">
            <div class="mx-3">
               <p class="p-card-body">fun filled place, really had lots of fun here</p>
            </div>
             <div class="d-flex justify-content-center py-1">
               <img src="/cars/16532.jpg" class="img-fluid" alt="...">
             </div>
          </div>
          <div class="card-footer mt-4 py-3 border-top" style="background-color:white; border:none">
               <div class="row row-footer">
                  <div class="col-4">
                    <div class="col-12 footer-div">
                      <i class="mdi mdi-thumb-up-outline"></i>
                      <p>20k</p>
                    </div>
                 </div>
                 <div class="col-4">
                     <div class="col-12 footer-div">
                      <i class="mdi mdi-message-outline"></i>
                      <p>12</p>
                     </div>
                 </div>
                 <div class="col-4">
                    <div class="col-12 footer-div">
                        <i class="mdi mdi-share-outline"></i>
                        <p class="">4</p>
                    </div>
                 </div>
               </div>
          </div>
       </div>
      
 <div class="card text-dark mt-4 p-0 m-0">
            <div class="card-header  d-flex  d-xl-flex justify-content-between">
                  <div class="preview-list">
                      <div class="preview-item">
                        <div class="preview-thumbnail">
                          <img src="/assets/images/faces/face6.jpg" alt="image" class="rounded-circle" />
                         <div class="active"></div>
                        </div>
                        <div class="preview-item-content d-flex flex-grow">
                          <div class="flex-grow">
                            <div class="d-flex d-md-block d-xl-flex justify-content-between">
                              <h6 class="preview-subject p-user-name">Silas Udofia</h6>
                            </div>
                            <span class="badge rounded-pill bg-primary">2 days ago</span>
                            <p class="text-muted p-card-header mt-2">Well, it seems to be working now.</p>
                          </div>
                        </div>
                      </div>
                 </div>
                  <p class="text-muted mt-2 small p-share p-1">Share</p>
          </div>
          <div class="card-body m-0 p-0">
            <div class="mx-3">
              <p class="p-card-body">Nature is amazing</p>
            </div>
            <div class="d-flex justify-content-center py-1">
               <img src="/cars/33116.jpg" class="img-fluid" alt="...">
            </div>
          </div>
          <div class="card-footer mt-4 py-3 border-top" style="background-color:white; border:none">
               <div class="row row-footer">
                  <div class="col-4">
                    <div class="col-12 footer-div">
                      <i class="mdi mdi-thumb-up-outline"></i>
                      <p>3k</p>
                    </div>
                 </div>
                 <div class="col-4">
                     <div class="col-12 footer-div">
                      <i class="mdi mdi-message-outline"></i>
                      <p>12</p>
                     </div>
                 </div>
                 <div class="col-4">
                    <div class="col-12 footer-div">
                        <i class="mdi mdi-share-outline"></i>
                        <p class="">4</p>
                    </div>
                 </div>
               </div>
          </div>
       </div> 



       <div class="card text-dark mt-4 p-0 m-0">
            <div class="card-header  d-flex  d-xl-flex justify-content-between">
                  <div class="preview-list">
                      <div class="preview-item">
                        <div class="preview-thumbnail">
                          <img src="/assets/images/faces/face6.jpg" alt="image" class="rounded-circle" />
                         <div class="active"></div>
                        </div>
                        <div class="preview-item-content d-flex flex-grow">
                          <div class="flex-grow">
                            <div class="d-flex d-md-block d-xl-flex justify-content-between">
                              <h6 class="preview-subject p-user-name">Silas Udofia</h6>
                            </div>
                            <span class="badge rounded-pill bg-primary">2 days ago</span>
                            <p class="text-muted p-card-header mt-2">Well, it seems to be working now.</p>
                          </div>
                        </div>
                      </div>
                 </div>
                  <p class="text-muted mt-2 small p-share p-1">Share</p>
          </div>
          <div class="card-body m-0 p-0">
            <div class="mx-3">
              <p class="p-card-body">Nature is amazing</p>
            </div>
            <div class="d-flex justify-content-center py-1">
               <img src="/cars/33119.jpg" class="img-fluid" alt="...">
            </div>
          </div>
          <div class="card-footer mt-4 py-3 border-top" style="background-color:white; border:none">
               <div class="row row-footer">
                  <div class="col-4">
                    <div class="col-12 footer-div">
                      <i class="mdi mdi-thumb-up-outline"></i>
                      <p>3k</p>
                    </div>
                 </div>
                 <div class="col-4">
                     <div class="col-12 footer-div">
                      <i class="mdi mdi-message-outline"></i>
                      <p>12</p>
                     </div>
                 </div>
                 <div class="col-4">
                    <div class="col-12 footer-div">
                        <i class="mdi mdi-share-outline"></i>
                        <p class="">4</p>
                    </div>
                 </div>
               </div>
          </div>
       </div> 



<div class="card text-dark mt-4 p-0 m-0">
            <div class="card-header  d-flex  d-xl-flex justify-content-between">
                  <div class="preview-list">
                      <div class="preview-item">
                        <div class="preview-thumbnail">
                          <img src="/assets/images/faces/face6.jpg" alt="image" class="rounded-circle" />
                         <div class="active"></div>
                        </div>
                        <div class="preview-item-content d-flex flex-grow">
                          <div class="flex-grow">
                            <div class="d-flex d-md-block d-xl-flex justify-content-between">
                              <h6 class="preview-subject p-user-name">Silas Udofia</h6>
                            </div>
                            <span class="badge rounded-pill bg-primary">2 days ago</span>
                            <p class="text-muted p-card-header mt-2">Well, it seems to be working now.</p>
                          </div>
                        </div>
                      </div>
                 </div>
                  <p class="text-muted mt-2 small p-share p-1">Share</p>
          </div>
          <div class="card-body m-0 p-0">
            <div class="mx-3">
              <p class="p-card-body">Nature is amazing</p>
            </div>
            <div class="d-flex justify-content-center py-1">
               <img src="/cars/33120.jpg" class="img-fluid" alt="...">
            </div>
          </div>
          <div class="card-footer mt-4 py-3 border-top" style="background-color:white; border:none">
               <div class="row row-footer">
                  <div class="col-4">
                    <div class="col-12 footer-div">
                      <i class="mdi mdi-thumb-up-outline"></i>
                      <p>3k</p>
                    </div>
                 </div>
                 <div class="col-4">
                     <div class="col-12 footer-div">
                      <i class="mdi mdi-message-outline"></i>
                      <p>12</p>
                     </div>
                 </div>
                 <div class="col-4">
                    <div class="col-12 footer-div">
                        <i class="mdi mdi-share-outline"></i>
                        <p class="">4</p>
                    </div>
                 </div>
               </div>
          </div>
       </div> 



<div class="card text-dark mt-4 p-0 m-0">
            <div class="card-header  d-flex  d-xl-flex justify-content-between">
                  <div class="preview-list">
                      <div class="preview-item">
                        <div class="preview-thumbnail">
                          <img src="/assets/images/faces/face6.jpg" alt="image" class="rounded-circle" />
                         <div class="active"></div>
                        </div>
                        <div class="preview-item-content d-flex flex-grow">
                          <div class="flex-grow">
                            <div class="d-flex d-md-block d-xl-flex justify-content-between">
                              <h6 class="preview-subject p-user-name">Silas Udofia</h6>
                            </div>
                            <span class="badge rounded-pill bg-primary">2 days ago</span>
                            <p class="text-muted p-card-header mt-2">Well, it seems to be working now.</p>
                          </div>
                        </div>
                      </div>
                 </div>
                  <p class="text-muted mt-2 small p-share p-1">Share</p>
          </div>
          <div class="card-body m-0 p-0">
            <div class="mx-3">
              <p class="p-card-body">Nature is amazing</p>
            </div>
            <div class="d-flex justify-content-center py-1">
               <img src="/cars/33130.jpg" class="img-fluid" alt="...">
            </div>
          </div>
          <div class="card-footer mt-4 py-3 border-top" style="background-color:white; border:none">
               <div class="row row-footer">
                  <div class="col-4">
                    <div class="col-12 footer-div">
                      <i class="mdi mdi-thumb-up-outline"></i>
                      <p>3k</p>
                    </div>
                 </div>
                 <div class="col-4">
                     <div class="col-12 footer-div">
                      <i class="mdi mdi-message-outline"></i>
                      <p>12</p>
                     </div>
                 </div>
                 <div class="col-4">
                    <div class="col-12 footer-div">
                        <i class="mdi mdi-share-outline"></i>
                        <p class="">4</p>
                    </div>
                 </div>
               </div>
          </div>
       </div> 


<div class="card text-dark mt-4 p-0 m-0">
            <div class="card-header  d-flex  d-xl-flex justify-content-between">
                  <div class="preview-list">
                      <div class="preview-item">
                        <div class="preview-thumbnail">
                          <img src="/assets/images/faces/face6.jpg" alt="image" class="rounded-circle" />
                         <div class="active"></div>
                        </div>
                        <div class="preview-item-content d-flex flex-grow">
                          <div class="flex-grow">
                            <div class="d-flex d-md-block d-xl-flex justify-content-between">
                              <h6 class="preview-subject p-user-name">Silas Udofia</h6>
                            </div>
                            <span class="badge rounded-pill bg-primary">2 days ago</span>
                            <p class="text-muted p-card-header mt-2">Well, it seems to be working now.</p>
                          </div>
                        </div>
                      </div>
                 </div>
                  <p class="text-muted mt-2 small p-share p-1">Share</p>
          </div>
          <div class="card-body m-0 p-0">
            <div class="mx-3">
              <p class="p-card-body">Nature is amazing</p>
            </div>
            <div class="d-flex justify-content-center py-1">
               <img src="/cars/33154.jpg" class="img-fluid" alt="...">
            </div>
          </div>
          <div class="card-footer mt-4 py-3 border-top" style="background-color:white; border:none">
               <div class="row row-footer">
                  <div class="col-4">
                    <div class="col-12 footer-div">
                      <i class="mdi mdi-thumb-up-outline"></i>
                      <p>3k</p>
                    </div>
                 </div>
                 <div class="col-4">
                     <div class="col-12 footer-div">
                      <i class="mdi mdi-message-outline"></i>
                      <p>12</p>
                     </div>
                 </div>
                 <div class="col-4">
                    <div class="col-12 footer-div">
                        <i class="mdi mdi-share-outline"></i>
                        <p class="">4</p>
                    </div>
                 </div>
               </div>
          </div>
       </div> 


<div class="card text-dark mt-4 p-0 m-0">
            <div class="card-header  d-flex  d-xl-flex justify-content-between">
                  <div class="preview-list">
                      <div class="preview-item">
                        <div class="preview-thumbnail">
                          <img src="/assets/images/faces/face6.jpg" alt="image" class="rounded-circle" />
                         <div class="active"></div>
                        </div>
                        <div class="preview-item-content d-flex flex-grow">
                          <div class="flex-grow">
                            <div class="d-flex d-md-block d-xl-flex justify-content-between">
                              <h6 class="preview-subject p-user-name">Silas Udofia</h6>
                            </div>
                            <span class="badge rounded-pill bg-primary">2 days ago</span>
                            <p class="text-muted p-card-header mt-2">Well, it seems to be working now.</p>
                          </div>
                        </div>
                      </div>
                 </div>
                  <p class="text-muted mt-2 small p-share p-1">Share</p>
          </div>
          <div class="card-body m-0 p-0">
            <div class="mx-3">
              <p class="p-card-body">Nature is amazing</p>
            </div>
            <div class="d-flex justify-content-center py-1">
               <img src="/cars/33155.jpg" class="img-fluid" alt="...">
            </div>
          </div>
          <div class="card-footer mt-4 py-3 border-top" style="background-color:white; border:none">
               <div class="row row-footer">
                  <div class="col-4">
                    <div class="col-12 footer-div">
                      <i class="mdi mdi-thumb-up-outline"></i>
                      <p>3k</p>
                    </div>
                 </div>
                 <div class="col-4">
                     <div class="col-12 footer-div">
                      <i class="mdi mdi-message-outline"></i>
                      <p>12</p>
                     </div>
                 </div>
                 <div class="col-4">
                    <div class="col-12 footer-div">
                        <i class="mdi mdi-share-outline"></i>
                        <p class="">4</p>
                    </div>
                 </div>
               </div>
          </div>
       </div> 


     
      </div>
     </div>
    </div>

    <div class="container">
   <div class="offcanvas offcanvas-start  w-50 h-50 bg-light" tabindex="-4" id="offcanvas" data-bs-keyboard="false" data-bs-backdrop="false">
    <div class="offcanvas-header">
        <h6 class="offcanvas-title d-none d-sm-block" id="offcanvas"><strong>Menu</strong></h6>
        <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
    </div>
    <div class="offcanvas-body  p-0 m-0">
        <ul class="nav nav-pills flex-column mb-sm-auto mb-0 align-items-start" id="menu">
           
           
            <li>
                <a href="#" class="nav-link text-truncate">
                 <span class="ms-1 d-none d-sm-inline">Products</span>
                 </a>
            </li>
            <li>
                <a href="#" class="nav-link text-truncate">
                 <span class="ms-1 d-none d-sm-inline">Customers</span> 
                 </a>
            </li>
        </ul>
    </div>
 </div>

 </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style>


</style>
