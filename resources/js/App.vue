<!-- eslint-disable -->
<template>
  <div id="main-wrapper">
    <header
      class="topbar"
      data-navbarbg="skin5"
    >
      <nav class="navbar top-navbar navbar-expand-md navbar-dark">
        <div
          class="navbar-header"
          data-logobg="skin5"
        >
          <!-- This is for the sidebar toggle which is visible on mobile only -->
          <a
            class="nav-toggler waves-effect waves-light d-block d-md-none"
            href="javascript:void(0)"
          >
            <i class="ti-menu ti-close" />
          </a>
          <router-link :to="'/home'" class="navbar-brand">
            <!-- Logo icon -->
            <b class="logo-icon p-l-10">
            </b>
            <!--End Logo icon -->
            <!-- Logo text -->
            <span class="logo-text">
              <!-- dark Logo text -->
              Catalog
            </span>
          </router-link>
          <a
            class="topbartoggler d-block d-md-none waves-effect waves-light"
            href="javascript:void(0)"
            data-toggle="collapse"
            data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <i class="ti-more" />
          </a>
        </div>
        <div
          id="navbarSupportedContent"
          class="navbar-collapse collapse"
          data-navbarbg="skin5"
        >
          <ul class="navbar-nav float-left mr-auto">
            <li class="nav-item d-none d-md-block">
              <a
                class="nav-link sidebartoggler waves-effect waves-light"
                href="javascript:void(0)"
                data-sidebartype="mini-sidebar"
              >
                <i class="mdi mdi-menu font-24" />
              </a>
            </li>
          </ul>
          <ul class="navbar-nav float-right">
            <!-- ============================================================== -->
            <!-- Comment -->
            <!-- ============================================================== -->
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle waves-effect waves-dark"
                href=""
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
              >
                <i class="mdi mdi-bell font-24" />
              </a>
              <div
                class="dropdown-menu"
                aria-labelledby="navbarDropdown"
              >
                <a
                  class="dropdown-item"
                  href="#"
                >
                  Action
                </a>
                <a
                  class="dropdown-item"
                  href="#"
                >
                  Another action
                </a>
                <div class="dropdown-divider" />
                <a
                  class="dropdown-item"
                  href="#"
                >
                  Something else here
                </a>
              </div>
            </li>
            <li class="nav-item dropdown">
              <a
                id="2"
                class="nav-link dropdown-toggle waves-effect waves-dark"
                href=""
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
              >
                <i class="font-24 mdi mdi-comment-processing" />
              </a>
              <div
                class="dropdown-menu dropdown-menu-right mailbox animated bounceInDown"
                aria-labelledby="2"
              >
                <ul class="list-style-none">
                  <li>
                    <div class="">
                      <!-- Message -->
                      <a
                        href="javascript:void(0)"
                        class="link border-top"
                      >
                        <div class="d-flex no-block align-items-center p-10">
                          <span class="btn btn-success btn-circle">
                            <i class="ti-calendar" />
                          </span>
                          <div class="m-l-10">
                            <h5 class="m-b-0">
                              Event today
                            </h5>
                            <span class="mail-desc">
                              Just a reminder that event
                            </span>
                          </div>
                        </div>
                      </a>
                      <!-- Message -->
                      <a
                        href="javascript:void(0)"
                        class="link border-top"
                      >
                        <div class="d-flex no-block align-items-center p-10">
                          <span class="btn btn-info btn-circle">
                            <i class="ti-settings" />
                          </span>
                          <div class="m-l-10">
                            <h5 class="m-b-0">
                              Settings
                            </h5>
                            <span class="mail-desc">
                              You can customize this template
                            </span>
                          </div>
                        </div>
                      </a>
                      <!-- Message -->
                      <a
                        href="javascript:void(0)"
                        class="link border-top"
                      >
                        <div class="d-flex no-block align-items-center p-10">
                          <span class="btn btn-primary btn-circle">
                            <i class="ti-user" />
                          </span>
                          <div class="m-l-10">
                            <h5 class="m-b-0">
                              Pavan kumar
                            </h5>
                            <span class="mail-desc">
                              Just see the my admin!
                            </span>
                          </div>
                        </div>
                      </a>
                      <!-- Message -->
                      <a
                        href="javascript:void(0)"
                        class="link border-top"
                      >
                        <div class="d-flex no-block align-items-center p-10">
                          <span class="btn btn-danger btn-circle">
                            <i class="fa fa-link" />
                          </span>
                          <div class="m-l-10">
                            <h5 class="m-b-0">
                              Luanch Admin
                            </h5>
                            <span class="mail-desc">
                              Just see the my new admin!
                            </span>
                          </div>
                        </div>
                      </a>
                    </div>
                  </li>
                </ul>
              </div>
            </li>
            <!-- ============================================================== -->
            <!-- End Messages -->
            <!-- ============================================================== -->

            <!-- ============================================================== -->
            <!-- User profile and search -->
            <!-- ============================================================== -->
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle text-muted waves-effect waves-dark pro-pic"
                href=""
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
              />
              <div class="dropdown-menu dropdown-menu-right user-dd animated">
                <a
                  class="dropdown-item"
                  href="javascript:void(0)"
                >
                  <i class="ti-user m-r-5 m-l-5" /> My Profile
                </a>
                <a
                  class="dropdown-item"
                  href="javascript:void(0)"
                >
                  <i class="ti-wallet m-r-5 m-l-5" /> My Balance
                </a>
                <a
                  class="dropdown-item"
                  href="javascript:void(0)"
                >
                  <i class="ti-email m-r-5 m-l-5" /> Inbox
                </a>
                <div class="dropdown-divider" />
                <a
                  class="dropdown-item"
                  href="javascript:void(0)"
                >
                  <i class="ti-settings m-r-5 m-l-5" /> Account Setting
                </a>
                <div class="dropdown-divider" />
                <a
                  class="dropdown-item"
                  href="javascript:void(0)"
                >
                  <i class="fa fa-power-off m-r-5 m-l-5" /> Logout
                </a>
                <div class="dropdown-divider" />
                <div class="p-l-30 p-10">
                  <a
                    href="javascript:void(0)"
                    class="btn btn-sm btn-success btn-rounded"
                  >
                    View Profile
                  </a>
                </div>
              </div>
            </li>
            <!-- ============================================================== -->
            <!-- User profile and search -->
            <!-- ============================================================== -->
          </ul>
        </div>
      </nav>
    </header>
    <!-- ============================================================== -->
    <!-- End Topbar header -->
    <!-- ============================================================== -->
    <!-- ============================================================== -->
    <!-- Left Sidebar - style you can find in sidebar.scss  -->
    <!-- ============================================================== -->
    <aside
      class="left-sidebar"
      data-sidebarbg="skin5"
    >
      <!-- Sidebar scroll-->
      <div class="scroll-sidebar">
        <!-- Sidebar navigation-->
        <nav class="sidebar-nav">
          <ul
            id="sidebarnav"
            class="p-t-30"
          >
            <li class="sidebar-item">
              <!-- <router-link to="/list-accounts"  class="sidebar-link waves-effect waves-dark sidebar-link" aria-expanded="false">
                <i class="mdi mdi-view-dashboard" /><span class="hide-menu">
                  Dashboard
                </span>
              </router-link> -->
            </li>
            <li class="sidebar-item">

              <router-link to="/category"  class="sidebar-link waves-effect waves-dark sidebar-link" aria-expanded="false">
                <i class="mdi mdi-chart-bar" /><span class="hide-menu">
                  Category
                </span>
              </router-link>
            </li>

            <li class="sidebar-item">
              <router-link to="/product"  class="sidebar-link waves-effect waves-dark sidebar-link" aria-expanded="false">
                <i class="mdi mdi-chart-bar" /><span class="hide-menu">
                  Product
                </span>
              </router-link>
            </li>
          </ul>
        </nav>
        <!-- End Sidebar navigation -->
      </div>
      <!-- End Sidebar scroll-->
    </aside>
    <div class="page-wrapper">
      <div class="page-breadcrumb">
        <div class="row">
          <div class="col-12 d-flex no-block align-items-center">
            <h4 class="page-title">
            </h4>
            <div class="ml-auto text-right">
              <!-- <nav aria-label="breadcrumb">
                <ol class="breadcrumb">
                  <li class="breadcrumb-item">
                    <a href="#">
                      Home
                    </a>
                  </li>
                  <li
                    class="breadcrumb-item active"
                    aria-current="page"
                  >
                    Library
                  </li>
                </ol>
              </nav> -->
            </div>
          </div>
        </div>
      </div>
      <div class="container-fluid">
        <div class="row">
          <!-- Column -->
          <div class="col-12">
            <router-view />
          </div>
        </div>
      </div>
      <footer class="footer text-center">
        All Rights Reserved by Catalog
      </footer>
    </div>
  </div>
</template>
<!-- eslint-enable -->
