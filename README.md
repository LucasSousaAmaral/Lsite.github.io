-<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8" />
  <link rel="apple-touch-icon" sizes="76x76" href="./assets/img/apple-icon.png">
  <link rel="icon" type="image/png" href="./assets/img/favicon.png">
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
  <title>
    Lderived Solutions
  </title>
  <meta content='width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0, shrink-to-fit=no' name='viewport' />
  <!--     Fonts and icons     -->
  <link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700|Roboto+Slab:400,700|Material+Icons" />
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/latest/css/font-awesome.min.css">
  <!-- CSS Files -->
  <link href="./assets/css/material-kit.css?v=2.0.6" rel="stylesheet" />
  <!-- CSS Just for demo purpose, don't include it in your project -->
  <link href="./assets/demo/demo.css" rel="stylesheet" />
</head>

<body class="index-page sidebar-collapse">
  <nav class="navbar navbar-transparent navbar-color-on-scroll fixed-top navbar-expand-lg" color-on-scroll="100" id="sectionsNav">
    <div class="container">
      <div class="navbar-translate">
        <a class="navbar-brand" href="#">
          LDerived Solutions </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" aria-expanded="false" aria-label="Toggle navigation">
          <span class="sr-only">Toggle navigation</span>
          <span class="navbar-toggler-icon"></span>
          <span class="navbar-toggler-icon"></span>
          <span class="navbar-toggler-icon"></span>
        </button>
      </div>
      <div class="collapse navbar-collapse">
        <ul class="navbar-nav ml-auto">
        
          <li class="nav-item">
            <a class="nav-link" href="javascript:void(0)" onclick="scrollToDownload()">
              <i class="material-icons">cloud_download</i> Downloads
            </a>
          </li>
            <li class="nav-item">
            <a class="nav-link" rel="tooltip" title="" data-placement="bottom" target="_blank"  data-original-title="LinkedIn é bom, mas tem que saber usar e o GitHub não é uma rede social!!!">
                Não usem redes sociais
                </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <div class="page-header header-filter clear-filter grey-filter" data-parallax="true" style="background-image: url('./assets/img/bg2.jpg');">
    <div class="container">
      <div class="row">
        <div class="col-md-8 ml-auto mr-auto">
          <div class="brand">
            <h1>Lderived Solutions</h1>
            <h3>Improve your code, to a better world</h3>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="main main-raised">
    <div class="section section-basic">
      <div class="container">
        <div class="title">
          <h2>Basic Elements</h2>
        </div>
        <!--  buttons -->
        <div id="buttons" class="cd-section">
          <div class="title">
            <h3>Buttons
              <br>
              <small>Pick your style</small>
            </h3>
          </div>
          <div class="row">
            <div class="col-md-8 ml-auto mr-auto">
              <button class="btn btn-primary">Default</button>
              <button class="btn btn-primary btn-round">Round</button>
              <button class="btn btn-primary btn-round">
                <i class="material-icons">favorite</i> With Icon
              </button>
              <button class="btn btn-primary btn-fab btn-round">
                <i class="material-icons">favorite</i>
              </button>
              <button class="btn btn-primary btn-link">Simple</button>
            </div>
          </div>
          <div class="title">
            <h3>
              <small>Pick your size</small>
            </h3>
          </div>
          <div class="row">
            <div class="col-md-8 ml-auto mr-auto">
              <button class="btn btn-primary btn-sm">Small</button>
              <button class="btn btn-primary">Regular</button>
              <button class="btn btn-primary btn-lg">Large</button>
            </div>
          </div>
          <div class="title">
            <h3>
              <small> Pick your color </small>
            </h3>
          </div>
          <div class="row">
            <div class="col-md-10 ml-auto">
              <button class="btn">Default</button>
              <button class="btn btn-primary">Primary</button>
              <button class="btn btn-info">Info</button>
              <button class="btn btn-success">Success</button>
              <button class="btn btn-warning">Warning</button>
              <button class="btn btn-danger">Danger</button>
              <button class="btn btn-rose">Rose</button>
            </div>
          </div>
        </div>
        <!--                 end buttons		         -->
        <div class="space-50"></div>
        <!--                 inputs -->
        <div id="inputs">
          <div class="title">
            <h3>Inputs</h3>
          </div>
          <div class="row">
            <div class="col-lg-3 col-sm-4">
              <div class="form-group has-default">
                <input type="text" class="form-control" placeholder="Regular">
              </div>
            </div>
            <div class="col-lg-3 col-sm-4">
              <div class="form-group">
                <label for="exampleInput1" class="bmd-label-floating">With Floating Label</label>
                <input type="email" class="form-control" id="exampleInput1">
                <span class="bmd-help">We'll never share your email with anyone else.</span>
              </div>
            </div>
            <div class="col-lg-3 col-sm-4">
              <div class="form-group has-success">
                <label for="exampleInput2" class="bmd-label-floating">Success input</label>
                <input type="text" class="form-control" id="exampleInput2">
                <span class="form-control-feedback">
                  <i class="material-icons">done</i>
                </span>
              </div>
            </div>
            <div class="col-lg-3 col-sm-4">
              <div class="form-group has-danger">
                <label for="exampleInput3" class="bmd-label-floating">Error input</label>
                <input type="email" class="form-control" id="exampleInput3">
                <span class="form-control-feedback">
                  <i class="material-icons">clear</i>
                </span>
              </div>
            </div>
            <div class="col-lg-3 col-sm-4">
              <div class="form-group">
                <div class="input-group">
                  <div class="input-group-prepend">
                    <span class="input-group-text">
                      <i class="material-icons">group</i>
                    </span>
                  </div>
                  <input type="text" class="form-control" placeholder="With Material Icons">
                </div>
              </div>
            </div>
            <div class="col-lg-3 col-sm-4">
              <div class="form-group">
                <div class="input-group">
                  <div class="input-group-prepend">
                    <span class="input-group-text">
                      <i class="fa fa-group"></i>
                    </span>
                  </div>
                  <input type="text" class="form-control" placeholder="With Font Awesome Icons">
                </div>
              </div>
            </div>
          </div>
        </div>
        <!--                 end inputs -->
        <div class="space-70"></div>
        <!--                 textarea/checkbox/radio/toggle -->
        <div id="checkRadios">
          <div class="row">
            <div class="col-lg-3 col-md-4 col-sm-6">
              <div class="title">
                <h3>Checkboxes</h3>
              </div>
              <div class="form-check">
                <label class="form-check-label">
                  <input class="form-check-input" type="checkbox" value=""> Unchecked
                  <span class="form-check-sign">
                    <span class="check"></span>
                  </span>
                </label>
              </div>
              <div class="form-check">
                <label class="form-check-label">
                  <input class="form-check-input" type="checkbox" value="" checked> Checked
                  <span class="form-check-sign">
                    <span class="check"></span>
                  </span>
                </label>
              </div>
              <div class="form-check disabled">
                <label class="form-check-label">
                  <input class="form-check-input" type="checkbox" value="" disabled> Disabled unchecked
                  <span class="form-check-sign">
                    <span class="check"></span>
                  </span>
                </label>
              </div>
              <div class="form-check disabled">
                <label class="form-check-label">
                  <input class="form-check-input" type="checkbox" value="" disabled checked> Disabled checked
                  <span class="form-check-sign">
                    <span class="check"></span>
                  </span>
                </label>
              </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6">
              <div class="title">
                <h3>Radio Buttons</h3>
              </div>
              <div class="form-check">
                <label class="form-check-label">
                  <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1"> Radio is off
                  <span class="circle">
                    <span class="check"></span>
                  </span>
                </label>
              </div>
              <div class="form-check">
                <label class="form-check-label">
                  <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios2" value="option2" checked> Radio is on
                  <span class="circle">
                    <span class="check"></span>
                  </span>
                </label>
              </div>
              <div class="form-check disabled">
                <label class="form-check-label">
                  <input class="form-check-input" type="radio" name="exampleRadios1" id="exampleRadios11" value="option1" disabled> Disabled radio is off
                  <span class="circle">
                    <span class="check"></span>
                  </span>
                </label>
              </div>
              <div class="form-check disabled">
                <label class="form-check-label">
                  <input class="form-check-input" type="radio" name="exampleRadio1" id="exampleRadios21" value="option2" checked disabled> Disabled radio is on
                  <span class="circle">
                    <span class="check"></span>
                  </span>
                </label>
              </div>
            </div>
            <div class="col-lg-3 col-md-4 col-sm-6">
              <div class="title">
                <h3>Toggle Buttons</h3>
              </div>
              <div class="togglebutton">
                <label>
                  <input type="checkbox" checked="">
                  <span class="toggle"></span>
                  Toggle is on
                </label>
              </div>
              <div class="togglebutton">
                <label>
                  <input type="checkbox">
                  <span class="toggle"></span>
                  Toggle is off
                </label>
              </div>
            </div>
          </div>
        </div>
        <div class="space-70"></div>
        <!--    progress/sliders -->
        <div id="progress">
          <div class="row">
            <div class="col-md-6">
              <div class="title">
                <h3>Progress Bars</h3>
              </div>
              <div class="progress progress-line-primary">
                <div class="progress-bar progress-bar-primary" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 30%;">
                  <span class="sr-only">60% Complete</span>
                </div>
              </div>
              <div class="progress progress-line-info">
                <div class="progress-bar progress-bar-info" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
                  <span class="sr-only">60% Complete</span>
                </div>
              </div>
              <div class="progress progress-line-danger">
                <div class="progress-bar progress-bar-success" style="width: 35%">
                  <span class="sr-only">35% Complete (success)</span>
                </div>
                <div class="progress-bar progress-bar-warning" style="width: 20%">
                  <span class="sr-only">20% Complete (warning)</span>
                </div>
                <div class="progress-bar progress-bar-danger" style="width: 10%">
                  <span class="sr-only">10% Complete (danger)</span>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="title">
                <h3>Pagination</h3>
              </div>
              <ul class="pagination pagination-primary">
                <!--
                            color-classes: "pagination-primary", "pagination-info", "pagination-success", "pagination-warning", "pagination-danger"
                        -->
                <li class="page-item">
                  <a href="javascript:void(0);" class="page-link">1</a>
                </li>
                <li class="page-item">
                  <a href="javascript:void(0);" class="page-link">...</a>
                </li>
                <li class="page-item">
                  <a href="javascript:void(0);" class="page-link">5</a>
                </li>
                <li class="page-item">
                  <a href="javascript:void(0);" class="page-link">6</a>
                </li>
                <li class="active page-item">
                  <a href="javascript:void(0);" class="page-link">7</a>
                </li>
                <li class="page-item">
                  <a href="javascript:void(0);" class="page-link">8</a>
                </li>
                <li class="page-item">
                  <a href="javascript:void(0);" class="page-link">9</a>
                </li>
                <li class="page-item">
                  <a href="javascript:void(0);" class="page-link">...</a>
                </li>
                <li class="page-item">
                  <a href="javascript:void(0);" class="page-link">12</a>
                </li>
              </ul>
              <ul class="pagination pagination-info">
                <li class="page-item">
                  <a href="javascript:void(0);" class="page-link"> prev</a>
                </li>
                <li class="page-item">
                  <a href="javascript:void(0);" class="page-link">1</a>
                </li>
                <li class="page-item">
                  <a href="javascript:void(0);" class="page-link">2</a>
                </li>
                <li class="active page-item">
                  <a href="javascript:void(0);" class="page-link">3</a>
                </li>
                <li class="page-item">
                  <a href="javascript:void(0);" class="page-link">4</a>
                </li>
                <li class="page-item">
                  <a href="javascript:void(0);" class="page-link">5</a>
                </li>
                <li class="page-item">
                  <a href="javascript:void(0);" class="page-link">next </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <!--                 end progress -->
        <!--                 sliders -->
        <div id="sliders">
          <div class="row">
            <div class="col-md-6">
              <div class="title">
                <h3>Sliders</h3>
              </div>
              <div id="sliderRegular" class="slider"></div>
              <div id="sliderDouble" class="slider slider-info"></div>
            </div>
            <div class="col-md-6 ml-auto">
              <div class="title">
                <h3>Badges </h3>
              </div>
              <span class="badge badge-pill badge-secondary">Default</span>
              <span class="badge badge-pill badge-primary">Primary</span>
              <span class="badge badge-pill badge-info">Info</span>
              <span class="badge badge-pill badge-success">Success</span>
              <span class="badge badge-pill badge-warning">Warning</span>
              <span class="badge badge-pill badge-danger">Danger</span>
              <span class="badge badge-pill badge-rose">Rose</span>
            </div>
          </div>
        </div>
        <!--                 end sliders -->
      </div>
    </div>
      <div class="container">
        <!--                 menu -->
        <div class="row">
          <div class="col-md-6">
            <div class="title">
              <h3>Menu</h3>
            </div>
            <nav class="navbar navbar-expand-lg bg-primary">
              <div class="container">
                <div class="navbar-translate">
                  <a class="navbar-brand" href="/presentation.html">Menu</a>
                  <button class="navbar-toggler" type="button" data-toggle="collapse" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="navbar-toggler-icon"></span>
                    <span class="navbar-toggler-icon"></span>
                    <span class="navbar-toggler-icon"></span>
                  </button>
                </div>
                <div class="collapse navbar-collapse">
                  <ul class="navbar-nav">
                    <li class="active nav-item">
                      <a href="#pablo" class="nav-link">Link</a>
                    </li>
                    <li class="nav-item">
                      <a href="#pablo" class="nav-link">Link</a>
                    </li>
                    <li class="dropdown nav-item">
                      <a href="#pablo" class="dropdown-toggle nav-link" data-toggle="dropdown">Dropdown</a>
                      <div class="dropdown-menu">
                        <h6 class="dropdown-header">Dropdown header</h6>
                        <a href="#pablo" class="dropdown-item">Action</a>
                        <a href="#pablo" class="dropdown-item">Another action</a>
                        <a href="#pablo" class="dropdown-item">Something else here</a>
                        <div class="dropdown-divider"></div>
                        <a href="#pablo" class="dropdown-item">Separated link</a>
                        <div class="dropdown-divider"></div>
                        <a href="#pablo" class="dropdown-item">One more separated link</a>
                      </div>
                    </li>
                  </ul>
                </div>
              </div>
            </nav>
          </div>
          <div class="col-md-6">
            <div class="title">
              <h3>Menu with Icons</h3>
            </div>
            <nav class="navbar navbar-expand-lg bg-info">
              <div class="container">
                <div class="navbar-translate">
                  <a class="navbar-brand" href="/presentation.html">Icons</a>
                  <button class="navbar-toggler" type="button" data-toggle="collapse" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="navbar-toggler-icon"></span>
                    <span class="navbar-toggler-icon"></span>
                    <span class="navbar-toggler-icon"></span>
                  </button>
                </div>
                <div class="collapse navbar-collapse">
                  <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                      <a href="#pablo" class="nav-link"><i class="material-icons">email</i></a>
                    </li>
                    <li class="nav-item">
                      <a href="#pablo" class="nav-link"><i class="material-icons">face</i></a>
                    </li>
                    <li class="dropdown nav-item">
                      <a href="#pablo" class="dropdown-toggle nav-link" data-toggle="dropdown">
                        <i class="material-icons">settings</i>
                        <b class="caret"></b>
                      </a>
                      <div class="dropdown-menu dropdown-menu-right">
                        <h6 class="dropdown-header">Dropdown header</h6>
                        <a href="#pablo" class="dropdown-item">Action</a>
                        <a href="#pablo" class="dropdown-item">Another action</a>
                        <a href="#pablo" class="dropdown-item">Something else here</a>
                        <div class="dropdown-divider"></div>
                        <a href="#pablo" class="dropdown-item">Separated link</a>
                        <div class="dropdown-divider"></div>
                        <a href="#pablo" class="dropdown-item">One more separated link</a>
                      </div>
                    </li>
                  </ul>
                </div>
              </div>
            </nav>
          </div>
        </div>
        <!-- 	            end menu -->
        <div class="title">
          <h3>Navigation</h3>
        </div>
      </div>
        <div class="navigation-example" style="background-image: url('./assets/img//bg.jpg');">
          <!--        rose navbar with search form -->
          <nav class="navbar navbar-expand-lg bg-rose">
            <div class="container">
              <div class="navbar-translate">
                <a class="navbar-brand" href="#0">Brand</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="sr-only">Toggle navigation</span>
                  <span class="navbar-toggler-icon"></span>
                  <span class="navbar-toggler-icon"></span>
                  <span class="navbar-toggler-icon"></span>
                </button>
              </div>
              <div class="collapse navbar-collapse">
                <ul class="navbar-nav">
                  <li class="nav-item active">
                    <a href="#pablo" class="nav-link">link</a>
                  </li>
                  <li class="nav-item">
                    <a href="#pablo" class="nav-link">link</a>
                  </li>
                </ul>
                <form class="form-inline ml-auto">
                  <div class="form-group has-white">
                    <input type="text" class="form-control" placeholder="Search">
                  </div>
                  <button type="submit" class="btn btn-white btn-raised btn-fab btn-round">
                    <i class="material-icons">search</i>
                  </button>
                </form>
              </div>
            </div>
          </nav>
          <!--        end rose navbar -->
          <!--        info navbar -->
          <nav class="navbar navbar-expand-lg bg-info">
            <div class="container">
              <div class="navbar-translate">
                <a class="navbar-brand" href="#0">Info Color</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="sr-only">Toggle navigation</span>
                  <span class="navbar-toggler-icon"></span>
                  <span class="navbar-toggler-icon"></span>
                  <span class="navbar-toggler-icon"></span>
                </button>
              </div>
              <div class="collapse navbar-collapse">
                <ul class="navbar-nav ml-auto">
                  <li class="active nav-item">
                    <a href="#pablo" class="nav-link">
                      Discover
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="#pablo" class="nav-link">
                      Profile
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="#pablo" class="nav-link">
                      Settings
                    </a>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
          <!--        end info navbar -->
          <!--        primary navbar  -->
          <nav class="navbar navbar-expand-lg bg-primary">
            <div class="container">
              <div class="navbar-translate">
                <a class="navbar-brand" href="#0">Primary Color</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="sr-only">Toggle navigation</span>
                  <span class="navbar-toggler-icon"></span>
                  <span class="navbar-toggler-icon"></span>
                  <span class="navbar-toggler-icon"></span>
                </button>
              </div>
              <div class="collapse navbar-collapse">
                <ul class="navbar-nav ml-auto">
                  <li class="active nav-item">
                    <a href="#pablo" class="nav-link">
                      <i class="material-icons">explore</i> Discover
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="#pablo" class="nav-link">
                      <i class="material-icons">account_circle</i> Profile
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="#pablo" class="nav-link">
                      <i class="material-icons">settings</i> Settings
                    </a>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
          <!--        end primary navbar -->
          <!--         inverse navbar with notifications     -->
          <nav class="navbar navbar-inverse navbar-expand-lg bg-dark" role="navigation-demo">
            <div class="container">
              <!-- Brand and toggle get grouped for better mobile display -->
              <div class="navbar-translate">
                <a class="navbar-brand" href="#0">Navbar with notification</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="sr-only">Toggle navigation</span>
                  <span class="navbar-toggler-icon"></span>
                  <span class="navbar-toggler-icon"></span>
                  <span class="navbar-toggler-icon"></span>
                </button>
              </div>
              <!-- Collect the nav links, forms, and other content for toggling -->
              <div class="collapse navbar-collapse">
                <ul class="navbar-nav ml-auto">
                  <li class="nav-item">
                    <a href="#pablo" class="nav-link">
                      Discover
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="#pablo" class="nav-link">
                      Wishlist
                    </a>
                  </li>
                  <li class="nav-item">
                    <a href="#pablo" class="btn btn-rose btn-raised btn-fab btn-round" data-toggle="dropdown">
                      <i class="material-icons">email</i>
                    </a>
                  </li>
                  <li class="dropdown nav-item">
                    <a href="#pablo" class="profile-photo dropdown-toggle nav-link" data-toggle="dropdown">
                      <div class="profile-photo-small">
                        <img src="./assets/img/faces/avatar.jpg" alt="Circle Image" class="rounded-circle img-fluid">
                      </div>
                    </a>
                    <div class="dropdown-menu dropdown-menu-right">
                      <h6 class="dropdown-header">Dropdown header</h6>
                      <a href="#pablo" class="dropdown-item">Me</a>
                      <a href="#pablo" class="dropdown-item">Settings and other stuff</a>
                      <a href="#pablo" class="dropdown-item">Sign out</a>
                    </div>
                  </li>
                </ul>
              </div>
              <!-- /.navbar-collapse -->
            </div>
            <!-- /.container-->
          </nav>
         
    <div class="section section-download" id="downloadSection">
      <div class="container">
        <div class="row text-center">
          <div class="col-md-8 ml-auto mr-auto">
            <h2>Petende usar uma de nossas soluções?</h2>
            <h4>Cause if you do, all of it can be yours for free young fella.</h4>
          </div>
          
        </div>
        <br>
        <br>
        <div class="row text-center">
          <div class="col-md-8 ml-auto mr-auto">
            <h2>Young Lucas why u trap so hard?</h2>
            <h4>Yo man, We've just launched Lderived Equities Viewer</h4>
          </div>
        </div>
        <div class="sharing-area text-center">
          <div class="row justify-content-center">
            <h3>Obrigado por nos apoiar!</h3>
          </div>
          <a id="github" href="https://github.com/LucasSousaAmaral" target="_blank" class="btn btn-raised btn-github">
            <i class="fa fa-github"></i> Star
          </a>
        </div>
      </div>
    </div>
  </div>
  <footer class="footer" data-background-color="black">
    <div class="container">
      <div class="copyright float-right">
        &copy;
        <script>
          document.write(new Date().getFullYear())
        </script>, made with l<i class="material-icons">favorite</i>ve by
        <a href="https://github.com/LucasSousaAmaral" target="_blank">Lucas monstro sagrado</a> for a better web.
      </div>
    </div>
  </footer>
  <!--   Core JS Files   -->
  <script src="./assets/js/core/jquery.min.js" type="text/javascript"></script>
  <script src="./assets/js/core/popper.min.js" type="text/javascript"></script>
  <script src="./assets/js/core/bootstrap-material-design.min.js" type="text/javascript"></script>
  <script src="./assets/js/plugins/moment.min.js"></script>
  <!--	Plugin for the Datepicker, full documentation here: https://github.com/Eonasdan/bootstrap-datetimepicker -->
  <script src="./assets/js/plugins/bootstrap-datetimepicker.js" type="text/javascript"></script>
  <!--  Plugin for the Sliders, full documentation here: http://refreshless.com/nouislider/ -->
  <script src="./assets/js/plugins/nouislider.min.js" type="text/javascript"></script>
  <!--  Google Maps Plugin    -->
  <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_KEY_HERE"></script>
  <!-- Control Center for Material Kit: parallax effects, scripts for the example pages etc -->
  <script src="./assets/js/material-kit.js?v=2.0.6" type="text/javascript"></script>
  <script>
    $(document).ready(function() {
      //init DateTimePickers
      materialKit.initFormExtendedDatetimepickers();

      // Sliders Init
      materialKit.initSliders();
    });


    function scrollToDownload() {
      if ($('.section-download').length != 0) {
        $("html, body").animate({
          scrollTop: $('.section-download').offset().top
        }, 1000);
      }
    }

  </script>
</body>

</html>
