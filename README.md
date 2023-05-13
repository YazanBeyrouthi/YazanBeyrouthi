
<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
  <meta http-equiv="X-UA-Compatible" content="IE=Edge" />

  <meta charset="UTF-8">

  <!-- IE10 meta tags -->
  <meta name="application-name" content="" />
  <meta name="msapplication-tooltip" content="Launch Microsoft Dynamics 365 Finance and Operations" />
  <meta name="msapplication-TileImage" content="Resources/Images/Tile144.png" />

  <meta name="msapplication-TileColor" content="#4a356F" />
  <meta name="msapplication-navbutton-color" content="#4a356F" />

  <title></title>
  <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="default" />
  <meta name="apple-mobile-web-app-capable" content="yes" />
  <link rel="apple-touch-icon" sizes="57x57" href="Resources/Images/Tile57.png" />
  <link rel="apple-touch-icon" sizes="72x72" href="Resources/Images/Tile72.png" />
  <link rel="apple-touch-icon" sizes="114x114" href="Resources/Images/Tile114.png" />
  <link rel="apple-touch-icon" sizes="144x144" href="Resources/Images/Tile144i.png" />

  <!-- Please keep above meta data at top of the file.  bug 2731835 -->

  <!-- css -->
     <style type='text/css'>
    #splashScreen {
      background-color: #FFFFFF;
      height: 100%;
      left: 0;
      opacity: 1;
      position: absolute;
      top: 0;
      width: 100%;
      z-index: 1000;
      color: #323130;
      align-items: center;
      text-align: center;
    }

    #MSLogo {
      position: fixed;
      bottom: 36px;
      width: 99px;
      height: 22px;
      left: calc(50% - (99px/2));
    }

    .dynamics-loader {
      position: absolute;
      top: 50%;
      left: calc(50%);
      transform: translate(-50%, -50%);
      width: 100%;
    }

    .logo-glyph {
      width: 96px;
      height: 96px;
    }

    .ms-suiteName {
      font-family: Segoe UI;
      font-size: 32px;
      line-height: 40px;
      margin-top: 30px;
    }

    .ms-productName {
      font-family: Segoe UI;
      font-size: 24px;
      line-height: 32px;
      margin-top: 24px;
    }

    .ms-Spinner {
      box-sizing: border-box;
      border-radius: 50%;
      border-width: 1.5px;
      border-style: solid;
      border-color: rgb(0, 120, 212) rgb(199, 224, 244) rgb(199, 224, 244);
      border-image: initial;
      animation-name: spinner-animation;
      animation-duration: 1.3s;
      animation-iteration-count: infinite;
      animation-timing-function: cubic-bezier(0.53, 0.21, 0.29, 0.67);
      width: 28px;
      height: 28px;
      margin-left: calc(50% - (28px/2));
      margin-top: 40px;
    }

    @keyframes spinner-animation
    {
      0% {
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg);
      }
      100% {
        -webkit-transform: rotate(360deg);
        transform: rotate(360deg);
      }
    }

    @media screen and (max-height: 500px) {
      .ms-suiteName {
        margin-top: 15px;
      }
      .ms-productName {
        margin-top: 12px;
      }
      .ms-Spinner {
        margin-top: 10px;
      }
      #MSLogo {
        bottom: 12px;
      }
    }
    @media screen and (max-height: 270px) {
      .dynamics-loader {
        height: 100%;
        margin: 10px;
      }
      #logo {
        height: 50px;
        width: 50px;
      }
      .ms-suiteName {
        font-size: 24px;
        line-height: 20px;
      }
      .ms-productName {
        font-size: 16px;
        line-height: 16px;
      }
      .ms-Spinner {
        height: 14px;
        width: 14px;
      }
      #MSLogo {
        bottom: 12px;
      }
    }
  </style>

  <link href="Resources/styles/ext/jquery.qtip-3.0.3.min.css" rel="stylesheet" type="text/css" />





  <script type="text/javascript" src="Resources/app-config.js"></script>
  <script type="text/javascript">
    if (typeof (msWriteProfilerMark) !== "undefined") {
      msWriteProfilerMark("initShell,StartTM");
    }

  </script>
  <script>window.dynEnableSavedSettings = true;</script>

  

  <!-- TODO: Need to evaluate the casing patterns for urls, is lower case better? -->
  <!-- TODO: Need to re-evaluate loading script order -->
  <script type="text/javascript" src="Scripts/ext/jquery-3.5.0.min.js"></script>
  <script type="text/javascript" src="Scripts/ext/jquery.qtip-3.0.3.min.js"></script>
    <script type="text/javascript" src="Scripts/ext/jquery-ui-1.13.2.min.js"></script>
  
  <script type="text/javascript" src="Scripts/ext/ua-parser.min.js"></script>

  <script type="text/javascript" src="Scripts/ext/globalize/1.0/globalize.js"></script>
    <!-- Represents the user current culture -->
  <script type="text/javascript" src="Scripts/ext/globalize/1.0/globalize.culture.js" charset="UTF-8"></script>
  
  <script type="text/javascript" src="Scripts/ext/moment-2.29.4.min.js"></script>
  <script type="text/javascript" src="Scripts/ext/moment-timezone-0.5.33.min.js"></script>
  <script type="text/javascript" src="Scripts/ext/hammer.min-2.0.8.js"></script>

 <!-- Based the user current culture/supported language -->
 <script src="Scripts/Localized/Labels.js"></script>
 <script src="Scripts/Computed/UserBranding.js"></script>

  <script type="text/javascript" src="Scripts/ext/react.17.0.1.min.js"></script>
  <script type="text/javascript" src="Scripts/ext/react-dom.17.0.1.min.js"></script>

  <link href='Resources/styles/ext/fixed-data-table.min.css' rel='stylesheet' type='text/css' />
  <script type='text/javascript' src='Scripts/ext/controlLibrary/release/controlLibrary.e8afe5cd59693b5502e5.min.js'></script>

  <script type="text/javascript" src="Scripts/dyn-core.min-7.0.22356.2.js"></script>
  <script type="text/plain" src="Scripts/dyn-core.min-7.0.22356.2.js.map"></script>

  
  
  



</head>
<body class="internetRestrictedOn">
<div id="splashScreen" style="display: block; visibility:hidden">
    <div class="dynamics-loader">
      <div>
        <div id="svgHolder"></div>
        <div id="appName" class="ms-suiteName"></div>
        <div class="ms-productName">Dynamics 365</div>
        <div class="ms-Spinner"></div>
      </div>
    </div>
    <svg id="MSLogo" xmlns="http://www.w3.org/2000/svg">
      <g fill="none" fill-rule="evenodd">
          <path d="M34.643 12.075l-.588 1.647h-.034c-.105-.387-.28-.934-.556-1.63l-3.15-7.897h-3.077V16.75h2.03V9.032c0-.476-.01-1.052-.03-1.711-.01-.333-.049-.6-.058-.804h.045c.103.473.21.834.287 1.075l3.776 9.16h1.42l3.748-9.243c.085-.211.175-.622.257-.992h.044c-.048.915-.09 1.75-.095 2.256v7.978h2.165V4.195h-2.956l-3.228 7.88z" fill="#737474"></path>
          <path d="M0 20.956h98.148V0H0z"></path>
          <path fill="#737474" d="M42.866 16.751h2.118V7.752h-2.118zM43.947 3.929c-.349 0-.653.119-.902.353a1.166 1.166 0 00-.378.883c0 .344.126.636.374.865.247.23.552.345.906.345s.66-.115.91-.345c.25-.23.379-.52.379-.865 0-.339-.125-.632-.37-.873a1.262 1.262 0 00-.919-.363M52.477 7.663a5.892 5.892 0 00-1.182-.127c-.971 0-1.838.209-2.574.62-.739.41-1.31.998-1.699 1.745-.386.745-.583 1.615-.583 2.585 0 .85.19 1.631.567 2.318.377.69.91 1.23 1.585 1.602.673.373 1.452.563 2.313.563 1.006 0 1.866-.201 2.554-.597l.027-.017v-1.94l-.089.066c-.312.227-.66.408-1.035.538a3.121 3.121 0 01-1.014.197c-.83 0-1.497-.26-1.982-.772-.485-.513-.73-1.233-.73-2.14 0-.912.255-1.651.761-2.196.504-.544 1.173-.82 1.986-.82.695 0 1.374.236 2.014.702l.09.063V8.011l-.029-.017c-.241-.135-.571-.246-.98-.331M59.452 7.597a2.17 2.17 0 00-1.415.507c-.358.296-.616.7-.814 1.207H57.2V7.753h-2.116v8.999H57.2v-4.603c0-.784.178-1.426.528-1.912.346-.48.806-.723 1.369-.723.19 0 .404.031.636.093.23.063.396.129.493.2l.09.064V7.737l-.034-.014c-.197-.083-.477-.126-.83-.126M66.885 14.465c-.397.499-.996.751-1.779.751-.777 0-1.39-.256-1.823-.766-.435-.51-.655-1.238-.655-2.163 0-.954.22-1.701.655-2.22.433-.516 1.04-.778 1.806-.778.743 0 1.335.25 1.758.744.426.496.642 1.237.642 2.202 0 .977-.203 1.728-.604 2.23m-1.683-6.929c-1.484 0-2.663.435-3.503 1.293-.84.857-1.265 2.044-1.265 3.527 0 1.41.415 2.543 1.235 3.368.82.826 1.936 1.245 3.316 1.245 1.438 0 2.593-.441 3.434-1.31.84-.87 1.265-2.045 1.265-3.493 0-1.433-.4-2.573-1.187-3.394-.789-.82-1.897-1.236-3.295-1.236M74.378 11.471c-.667-.268-1.095-.49-1.27-.66-.17-.165-.257-.398-.257-.693 0-.262.108-.472.327-.642.219-.17.526-.257.911-.257.357 0 .723.056 1.085.166.363.111.682.26.949.44l.088.06V7.928l-.035-.015a4.715 4.715 0 00-.962-.268 5.932 5.932 0 00-1.056-.109c-1.01 0-1.845.258-2.483.767-.64.512-.967 1.184-.967 1.997 0 .422.07.798.209 1.116.14.32.355.6.641.837.283.233.722.478 1.302.728.488.2.852.37 1.083.505.227.13.387.263.477.39.088.127.133.299.133.512 0 .604-.452.897-1.384.897a3.8 3.8 0 01-1.172-.213 4.418 4.418 0 01-1.2-.609l-.089-.064v2.064l.033.015c.304.14.686.257 1.137.35.449.094.859.141 1.213.141 1.096 0 1.977-.26 2.62-.771.648-.515.976-1.204.976-2.045 0-.607-.176-1.127-.525-1.546-.345-.416-.946-.799-1.784-1.136M84.063 14.465c-.398.499-.997.751-1.78.751-.777 0-1.39-.256-1.822-.766-.435-.51-.655-1.238-.655-2.163 0-.954.22-1.701.655-2.22.432-.516 1.04-.778 1.806-.778.743 0 1.335.25 1.758.744.426.496.642 1.237.642 2.202 0 .977-.204 1.728-.604 2.23M82.38 7.536c-1.484 0-2.663.435-3.503 1.293-.84.857-1.266 2.044-1.266 3.527 0 1.41.415 2.543 1.235 3.368.82.826 1.936 1.245 3.317 1.245 1.438 0 2.593-.441 3.433-1.31.84-.87 1.266-2.045 1.266-3.493 0-1.433-.4-2.573-1.187-3.394-.789-.82-1.897-1.236-3.295-1.236M98.149 9.48V7.752h-2.144V5.069l-.072.022-2.015.616-.038.012v2.034h-3.177V6.62c0-.527.118-.931.351-1.2.23-.266.56-.402.982-.402.303 0 .616.072.931.213l.079.035V3.447l-.037-.013c-.294-.105-.695-.159-1.19-.159-.626 0-1.194.136-1.689.406-.495.27-.886.655-1.16 1.146-.272.489-.41 1.054-.41 1.68v1.246h-1.492v1.726h1.493v7.273h2.142V9.479h3.177v4.622c0 1.903.897 2.868 2.668 2.868.291 0 .597-.034.91-.101.319-.07.535-.137.662-.21l.029-.016v-1.743l-.087.058c-.117.078-.262.14-.432.188-.17.048-.312.072-.422.072-.416 0-.723-.112-.914-.332-.191-.223-.289-.612-.289-1.158V9.48h2.144z">
          </path>
          <path fill="#F05124" d="M0 9.958h9.958V.001H0z"></path>
          <path fill="#7EBB42" d="M10.995 9.958h9.957V.001h-9.957z"></path>
          <path fill="#32A0DA" d="M0 20.956h9.958V11H0z"></path>
          <path fill="#FDB813" d="M10.995 20.956h9.957V11h-9.957z"></path>
      </g>
    </svg>
  </div>
  <!-- update splash screen data -->
  <script type="text/javascript">
          if (window.location.search.toLowerCase().indexOf('hidesplash=true') === -1 && window.location.search.toLowerCase().indexOf('debug=vs') === -1) {
        var splashContainer = document.getElementById('splashScreen');
        if (splashContainer) {
          splashContainer.style.visibility = "visible";
        }
        var titleElement = document.getElementById('appName');
        if (titleElement) {
          if ($dyn.appConfig.appTitle !== undefined) {
            titleElement.innerHTML = $dyn.appConfig.appTitle;
          } else {
            titleElement.innerHTML = 'Finance and Operations';
          }
        }

        var logoElement = document.getElementById('svgHolder');
        if (logoElement) {
          if ($dyn.appConfig.splashLogoSVG !== undefined) {
            logoElement.innerHTML = $dyn.appConfig.splashLogoSVG;
          }
        }
      }
      </script>
<div id="mainContainer" class="mainContainer applicationShell-contentRegion" tabindex="-1" style="display:-webkit-flex;display:flex;">
    <div id="mainPane" role="presentation" class="mainPane binding-focusRegion" data-dyn-focus-region="MainPane">
        <div id="AriaAlertArea" role="alert" class="hidden" aria-live="assertive" aria-relevant="all" aria-atomic="true" ></div>
        <div id="MessageCenterEmbedded" class="navigationBar-pinnedElement" data-dyn-controlname="EmbeddedBar" data-dyn-role="MessageCenterButton"></div>
        <div id="NavBar" data-dyn-role="NavigationBar">
            <div id="NavigationSearch" class="navigationBar-pinnedElement" data-dyn-role="NavigationSearchButton"></div>
            <div id="User" class="navigationBar-user" data-dyn-role="UserButton"></div>
            <div id="Company" class="navigationBar-company navigationBar-pinnedElement" data-dyn-role="CompanyButton"></div>
        </div>
        <div id="PopoutNavBar" data-dyn-role="PopoutNavigationBar">
            <div id="PopoutUser" class="navigationBar-user" data-dyn-role="PopoutUserButton"></div>
            <div id="PopoutCompany" class="navigationBar-company" data-dyn-role="PopoutCompanyButton"></div>
        </div>
        <div class="modulesPane"></div>
        <div role="presentation" action="javascript:void(0)">
            <div class="primaryConductor" role="main" id="PrimaryConductor" style="display: block;"></div>
        </div>
    </div>
    <aside id="asidePane" class="asidePane left-splitter binding-focusRegion" data-dyn-focus-region="AsidePane" data-dyn-bind="
        resizable: { handles: 'w', zIndex: 'auto', resize: $dyn.shell._asidePaneStartResize, stop: $dyn.shell._asidePaneStopResize },
        focusIn: $dyn.shell.asidePaneFocusHandler"
        tabindex="-1" aria-hidden="true">
    </aside>
</div>

<div tabindex="-1"
     id="ShellBlockingDiv"
     class="applicationShell-blockingMessage unselectable"
     style="display: none;"
     data-dyn-bind="click: $dyn.shell.animateBlockingText, keyDown: $dyn.shell.blockingDivKeydown">
    <div id="ShellProcessingDiv" class="applicationShell-blockingMessageText">
        <span id="blockingMessage" data-dyn-bind="text: $label('Shell_ProcessingMessage')"></span>
    </div>
</div>

<div tabindex="-1"
     id="npsServiceModal"
     class="npsServiceModal unselectable"
     style="display: none;">
</div>

<div tabindex="-1" id="DisconnectedDiv" class="applicationShell-disconnectedMessage" style="display: none;"></div>

<div id="O365Switcher" class="o365-waffle-switcher" style="display: none;">
    <div id="O365Launcher" class="o365-waffle-launcher"></div>
</div>

<div id="ChordNotification" class="applicationShell-chordMessage fadeIn" role="alert" style="display: none;"></div>

<div class="dyn_templates" style="display: none;">
<div id="PopoutNavigationBar"
       class="popout navigationBar layout-root-scope"
       data-dyn-bind="
       vars: {$navBar: $data}"
       data-dyn-controlname="PopoutNavigationBar"
       data-dyn-container="true">
    <div class="navigationBar-staticLogo">
        <span class="navigationBar-staticLabel" data-dyn-bind="text: $dyn.shell.ProductName"></span>
        <span class="navigationbar-dashboard-operatedBy" data-dyn-bind="text: $dyn.shell.OperatedByName, visible: $dyn.value($dyn.shell.OperatedByName) != ''"></span>
    </div>
    <div class="navigationBar-actions">
        <div id="dynNavigationBarUserCompany" data-dyn-content="replace: '#PopoutCompany'"></div>
        <div id="dynNavigationBarUser" data-dyn-content="replace: '#PopoutUser'"></div>
    </div>
</div>

<nav id="NavigationBar" role="banner"
       class="navigationBar layout-root-scope"
       data-dyn-bind="
       vars: {$navBar: $data},
       attr: {'aria-label': $dyn.label('NavBar_Landmark')}"
       data-dyn-controlname="NavigationBar"
       data-dyn-container="true">
    <div class="navigationBar-launch">
        <button data-dyn-role="Button"
                data-dyn-controlname="NavBarOfficeWaffle"
                class="navigationBar-symbolButton navigationBar-officeWaffle "
                role="link"
                data-dyn-bind="
                    ImageType: 'Symbol',
                    ImageName: 'WaffleOffice365',
                    ButtonDisplay: $dyn.ui.ButtonDisplay.imageOnly,
                    Label: $label('NavBar_OfficeWaffle'),
                    HelpText: $label('NavBar_OfficeWaffleHelpText'),
                    Click: function(){ $dyn.shell.navigateUrl({ openInNewTab: true, url: $dyn.label('NavBar_OfficePortalUrl') }) }
        "></button>
        <button data-dyn-role="Button"
                data-dyn-controlname="NavBarDashboard"
                class="navigationBar-dashboardButton"
                data-dyn-bind="
                    css: { 'navBar-separator' : !$dyn.value($data.OfficeNavBarVisible) },
                    HelpText: $dyn.shell.ProductShortNameHelpText,
                    Label: $dyn.shell.ProductName,
                    Click: function() {$dyn.ui.getNavBar().navigateToDashboard(); }">
            <span class="navigationbar-dashboard-operatedBy" data-dyn-bind="text: $dyn.shell.OperatedByName, visible: $dyn.value($dyn.shell.OperatedByName) != ''"></span>
        </button>
    </div>
    <ol class="navigationBar-crumbList" data-dyn-bind="visible: !$dyn.value($data.OfficeNavBarVisible) ,foreach:$data.Crumbs">
        <li class="navigationBar-crumbItem D365ChevronRight-symbol"
            data-dyn-bind="
                text: $data,
                skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></li>
    </ol>
    <div id="navigationMainActionGroup" role="presentation" class="navigationBar-actions">
        <div id="dynNavigationBarUserCompany" data-dyn-content="replace: '#Company'"></div>
        <div id="coreNavActions" class="navigationBar-actions navigationBar-list">
            <ul class="navigationBar-list"
                data-dyn-bind="foreach: $navBar.actions">
                <li class="navigationBar-listItem">
                    <button class="navigationBar-symbolButton" data-dyn-role="Button"
                            data-dyn-bind="
                                Name: 'NavBar' + $data.Label,
                                ImageType: $dyn.value($data.ImageType) || 'Symbol',
                                ImageName: $data.Symbol,
                                ButtonDisplay: $data.ButtonDisplay || $dyn.ui.ButtonDisplay.textWithImageLeft,
                                Click: $data.Click,
                                Title: $data.Label,
                                Visible: $data.Visible,
                                ExtendedStyle: $data.Style,
                                Label: $data.Text,
                                Init: $dyn.applyFunction($data.Init, $element),
                    "></button>
                </li>
            </ul>
            <div id="dynNavigationBarSearch" data-dyn-content="replace: '#NavigationSearch'"></div>
            <div data-dyn-role="CombinedSearch" data-dyn-bind="Name: 'CombinedSearch'"></div>
            <div id="dynNavigationBarMessages" class="navigationBar-pinnedElement" data-dyn-role="MessageCenterButton"></div>
            <div role="presentation" data-dyn-bind="if: !$dyn.value($data.OfficeNavBarVisible)">
                <button class="navigationBar-symbolButton" data-dyn-role="Button"
                    data-dyn-bind="
                                Name: 'navBarFeedback',
                                Label: $dyn.label('NavBar_Feedback'),
                                HelpText: $dyn.label('NavBar_FeedbackHelpText'),
                                ButtonDisplay: $dyn.ui.ButtonDisplay.imageOnly,
                                ImageType: 'Symbol',
                                ImageName: 'Smiley',
                                Click: function () { $dyn.ui.feedBack() },"></button>
            </div>
            <span data-dyn-bind="css: { 'navBar-separator' : !$dyn.value($data.OfficeNavBarVisible) }"></span>
             <div data-dyn-role="MenuButton"
                 class="navigationBar-symbolButton navigationBar-settingsButton"
                 data-dyn-controlname="navBarSettings"
                 data-dyn-bind="Title: $label('NavBar_Settings'),
                                HelpText: $dyn.label('NavBar_SettingsHelpText'),
                                ImageName: 'Settings',
                                ImageType: 'Symbol',
                                ButtonDisplay: $dyn.ui.ButtonDisplay.imageOnly,
                                Label:  $label('NavBar_Settings'),
                            ">
                <div data-dyn-bind="inlineForeach: $navBar.settingsMenu">
                    <button data-dyn-role="MenuItem"
                            data-dyn-bind="
                                    Name: 'NavBar' + $data.Label,
                                    Click: $data.Click,
                                    Visible: $data.Visible,
                                    Label: $data.Label,
                    "></button>
                </div>
            </div>
            <div data-dyn-role="MenuButton"
                 class="navigationBar-symbolButton navigationBar-helpButton"
                 data-dyn-controlname="navBarHelpButton"
                 data-dyn-bind="Title: $label('NavBar_HelpMenu'),
                                HelpText: $dyn.label('NavBar_HelpMenuText'),
                                ImageName: 'Help',
                                ImageType: 'Symbol',
                                ButtonDisplay: $dyn.ui.ButtonDisplay.imageOnly,
                                Label:  $label('NavBar_HelpMenu')
                 ">
                <div data-dyn-bind="inlineForeach: $navBar.helpMenu">
                    <button data-dyn-role="MenuItem"
                            data-dyn-bind="
                            Name: 'NavBar' + $data.Label,
                            Click: $data.Click,
                            Visible: $data.Visible,
                            Label: $data.Label,
                            HelpText: $data.HelpText,
                            "></button>
                </div>
            </div>
            <div data-dyn-role="MenuButton"
                 class="navigationBar-symbolButton navigationBar-overflowButton navigationBar-pinnedElement"
                 data-dyn-controlname="navBarOverflow"
                 data-dyn-bind="
                    Title: $label('NavBar_Overflow'),
                    Visible: $navBar.ShowOverflowButton,
                    ShowLabel: false,
                    Label: $label('NavBar_Overflow'),
                    ">
                <div data-dyn-bind="inlineForeach: $navBar.overflowMenu">
                    <button data-dyn-role="MenuItem"
                            data-dyn-bind="
                                    Name: 'NavBar' + $data.Label,
                                    Click: $data.Click,
                                    Visible: $data.Visible,
                                    Label: $data.Label,
                    "></button>
                </div>
            </div>
            <div id="dynNavigationBarUser" data-dyn-content="replace: '#User'"></div>
        </div>
    </div>
</nav>
<div id="FeedbackPane" data-dyn-bind="Caption: $label('FeedbackPane_Caption')">
    <div class="feedbackpane" data-dyn-bind="layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }, sizing: { height: $dyn.layout.Size.content }, visible: true">
        <span data-dyn-role="Label" data-dyn-bind="Text: $format($label('FeedbackPane_IntroText'), $dyn.shell.ProductShortName())"></span>
        <div>
            <button data-dyn-role="ToggleButton" data-dyn-controlname="FeedbackPane_LikeButton"
                    data-dyn-bind="
                Label: $label('FeedbackPane_Like'),
                Toggled: $data.Liked,
                Click: function () { $data.ToggleFeedbackType($dyn.telemetry.FeedbackType.positive); },
                ImageType: 'Symbol',
                ImageName: 'Like'"></button>
            <button data-dyn-role="ToggleButton" data-dyn-controlname="FeedbackPane_DislikeButton"
                    data-dyn-bind="
                Label: $label('FeedbackPane_Dislike'),
                Toggled: $data.Disliked,
                Click: function () { $data.ToggleFeedbackType($dyn.telemetry.FeedbackType.negative); },
                ImageType: 'Symbol',
                ImageName: 'Dislike'"></button>
        </div>

        <div data-dyn-role="MultilineInput" data-dyn-controlname="FeedbackPane_Text" data-dyn-bind="Label: $label('NavBar_Feedback'), ShowLabel: false, Value: $data.Text, DisplayHeight: 12, UseHeightInRows: true, LayoutWidth: $dyn.layout.Size.available"></div>

        <span data-dyn-role="Label" data-dyn-bind="Text: $label('FeedbackPane_Privacy'), LayoutWidth: $dyn.layout.Size.available"></span>
        <a data-dyn-role="HyperLink" data-dyn-bind="BaseUrl: $label('NavBar_PrivacyUrl'), OpenInNewWindow: true, Text: $label('FeedbackPane_PrivacyLinkText')"></a>

        <div data-dyn-role="Group" data-dyn-bind="Label: $label('FeedbackPane_BrowserSessionHeader'), LayoutWidth: $dyn.layout.Size.available">
            <div data-dyn-role="Group" data-dyn-bind="ArrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft ">
                <div class="staticText" data-dyn-bind="text: $data.BrowserSessionActivityId,visible:$data.ShowSessionId"></div>
                <div class="staticText" data-dyn-bind="text: $data.BrowserSessionActivityId,visible:$data.ShowSessionIdAnchor"></div>
            </div>
            <div data-dyn-role="Label" data-dyn-bind="Text: $data.BrowserInteractionTimestamp"></div>
            <div data-dyn-role="Label" data-dyn-bind="Text: $data.AOSRoleInstance"></div>
            <div data-dyn-role="Label" data-dyn-bind="Text: $data.ActivityId, Visible: $data.ShowActivityId"></div>
            <div data-dyn-role="Label" data-dyn-bind="Text: $dyn.user().UserGuid"></div>
            <div data-dyn-role="Label" data-dyn-bind="Text: $data.AOSId"></div>
        </div>
         <div>
              <br/>
              <button data-dyn-role="Button" data-dyn-controlname="FeedbackPane_SubmitButton" data-dyn-bind="Label: $label('FeedbackPane_SubmitButton'), Click: function () { $data.Submit(); }"></button>
              <button data-dyn-role="Button" data-dyn-controlname="FeedbackPane_CancelButton" data-dyn-bind="Label: $label('FeedbackPane_CancelButton'), Click: function () { $data.Cancel(); }"></button>
         </div>
      </div>
</div>


<button id="Button" class="button dynamicsButton" type="button" data-dyn-bind="
    visible: $data.Visible,
    enabled: $data.Enabled,
    click: { callBack: $data.Clicked, optOutOfAllowSave: true },
    keyDown: $data.keyDown,
    ariaPressed: $data.Toggled,
    skip: $dyn.ui.skip($data),
    superTooltip: $dyn.ui.superTooltip($data),
    attr: {
        'name': $data.Name,
        'data-dyn-button-display': $data.buttonDisplay,
    },
    sizing: $dyn.layout.sizing($data),
    css: { 'button-isDefault' : $data.DefaultButton,
           'button-attachment-count' : $dyn.value($data.IsLabelBubble) }">
    <div class="button-container">
        <span class="button-commandRing" data-dyn-bind="img: $dyn.ui.img($data)"></span>
        <span class="button-help"
            data-dyn-bind="
                id: $data.Id + '_helptext',
                text: $dyn.value($data.HelpText)"
            style="display: none; visibility: hidden;">
        </span>
        <span data-dyn-bind="
            id: $data.Id + '_label', 
            ariaLabelFor: $dyn.ui.ariaLabelFor($data.Id, $data),
            css: { 'button-label' : !$dyn.value($data.IsLabelBubble),
                   'button-attach-label' : $dyn.value($data.IsLabelBubble) },
            attr: {
                'aria-describedby': $dyn.ui.getDescribedByData($data),
            }">
        </span>
    </div>
</button>

<button id="SymbolButton" class="button dynamicsButton" type="button" data-dyn-button-display="ImageOnly" data-dyn-bind="
    visible: $data.Visible,
    enabled: $data.Enabled,
    click: { callBack: $data.Clicked, optOutOfAllowSave: true },
    keyDown: $data.keyDown,
    ariaPressed: $data.Toggled,
    superTooltip: $dyn.ui.superTooltip($data),
    skip: $dyn.ui.skip($data),
    attr: {
        'name': $data.Name,
    },
    ariaLabel: $dyn.ui.ariaLabel($data),
    sizing: $dyn.layout.sizing($data)">
    <div class="button-container">
        <span class="button-commandRing" data-dyn-bind="img: $dyn.ui.img($data)"></span>
    </div>
</button>

<a id="AnchorButton" class="anchorButton" role="link" onclick="return false;" data-dyn-bind="
    visible: $data.Visible,
    enabled: $data.Enabled,
    click: { callBack: $data.Clicked, optOutOfAllowSave: true },
    skip: $dyn.ui.skip($data),
    keyDown: $data.keyDown,
    superTooltip: $dyn.ui.superTooltip($data),
    sizing: $dyn.layout.sizing($data),
    css: { 'button-isDefault' : $data.DefaultButton },
    attr: {
        'name': $data.Name,
        'data-dyn-button-display': $data.buttonDisplay,
    }">
    <div class="button-image" data-dyn-bind="img: $dyn.ui.img($data)"></div>
    <div class="button-textContainer">
        <span class="button-help" data-dyn-bind="id: $data.Id + '_helptext', text: $dyn.value($data.HelpText)" style="display: none; visibility: hidden;"></span>
        <span class="button-label" 
            data-dyn-bind="
                id: $data.Id + '_label',
                ariaLabelFor: $dyn.ui.ariaLabelFor($data.Id, $data),
                attr: {
                    'aria-describedby': $dyn.ui.getDescribedByData($data),
                }">
        </span>
    </div>
</a>

<button id="DropDialogButton" class="button dynamicsButton dropDialogButton" onclick="event.preventDefault();"
    type="button" data-dyn-bind="
    visible: $data.Visible,
    skip: $dyn.ui.skip($data),
    enabled: $data.Enabled,
    keyDown: $data.keyDown,
    sizing: $dyn.layout.sizing($data),
    superTooltip: $dyn.ui.superTooltip($data),
    attr: { 
        'name': $data.Name,
        'data-dyn-button-display': $data.buttonDisplay,
    },
    css: { 'button-isDefault' : $data.DefaultButton },
    flyout: { requestPopup: $data.showPopup, show: $data.ShowFlyout, positionResize: true }">
    <div class="button-container">
        <span class="button-commandRing" data-dyn-bind="img: $dyn.ui.img($data)"></span>
        <span class="button-help" data-dyn-bind="id: $data.Id + '_helptext', text: $dyn.value($data.HelpText)" style="display: none; visibility: hidden;"></span>
        <span class="button-label button-label-dropDown" data-dyn-bind="id: $data.Id + '_label', ariaLabelFor: $dyn.ui.ariaLabelFor($data.Id, $data),
            attr: {
                'aria-describedby': $dyn.ui.getDescribedByData($data),
            }">
        </span>
    </div>
</button>

<button id="MenuItem" class="button flyout-menuItem" role="menuitem" type="button" data-dyn-bind="
    visible: $data.Visible,
    enabled: $data.Enabled,
    click: { callBack: $data.Clicked, optOutOfAllowSave: true },
    keyDown: $data.keyDown,
    selected: $data.Selected,
    skip: $dyn.ui.skip($data),
    superTooltip: $dyn.ui.superTooltip($data),
    attr: {
        'name': $data.Name,
        'data-dyn-button-display': $data.buttonDisplay,
        'aria-label': $data.Label,
    },
    css: { 'button-isDefault' : $data.DefaultButton }">
    <div class="button-container">
        <span class="button-commandRing" data-dyn-bind="img: $dyn.ui.img($data)"></span>
        <span class="button-help" data-dyn-bind="id: $data.Id + '_helptext', text: $dyn.value($data.HelpText)" style="display: none; visibility: hidden;"></span>
        <span class="button-label" data-dyn-bind="id: $data.Id + '_label', ariaLabelFor: $dyn.ui.ariaLabelFor($data.Id, $data, $data.Label),
            attr: {
                'aria-describedby': $dyn.ui.getDescribedByData($data),
            }">
        </span>
    </div>
</button>

<div id="MenuButton" data-dyn-bind="visible: $data.Visible" class="flyoutContainer" data-dyn-focus=".dynamicsButton"  data-dyn-container=".flyoutButton-flyOut">
    <button class="button flyoutButton-Button dynamicsButton" aria-haspopup="true" type="button" onclick="event.preventDefault();" data-dyn-bind="
        keyDown: $data.keyDown,
        id: $data.Id + '_button',
        enabled: $data.Enabled,
        skip: $dyn.ui.skip($data),
        sizing: $dyn.layout.sizing($data),
        superTooltip: $dyn.ui.superTooltip($data),
        css: { 'button-isDefault' : $data.DefaultButton },
        flyout: { flyout: $('.sysPopup', $element.parentElement), show: $data.ShowFlyout,
            clickSubscriber: $dyn.util.flyout.getFlyoutWithActionsClickSubscriber('button:enabled'), positionResize: true, optOutOfWait: $dyn.value($data.HasBeenOpened), getAnchor: $data.getCurrentAnchor
        },
        ariaLabelledBy: { byElementId: $data.Id + '_label', showLabel: $data.ShowLabel, isInGrid: $data._isInGrid },
        attr: {
            'name': $data.Name,
            'data-dyn-button-display': $data.buttonDisplay,
            'aria-controls': $data.Id + '_list',
            'aria-describedby': $data.Id + '_helptext',
        }">
        <div class="button-container">
            <span class="button-commandRing" data-dyn-bind="img: $dyn.ui.img($data)"></span>
            <span class="button-label button-label-dropDown" data-dyn-bind="id: $data.Id + '_label', ariaLabelFor: $dyn.ui.ariaLabelFor('', $data),
                attr: {
                    'aria-describedby': $dyn.ui.getDescribedByData($data),
                }">
            </span>
        </div>
    </button>
    <div class="sysPopup flyoutButton-flyOut layout-root-scope" data-dyn-content="append: '*'" role="menu" tabindex="-1" data-dyn-bind="
        attr: { 'aria-hidden': !$data.ShowFlyout, },
        id: $data.Id + '_list'"></div>
    <span data-dyn-role="FieldHelpSection" data-dyn-bind="Id: $data.Id, HelpText: $data.HelpText"></span>
</div>

<div id="MenuItemSeparator" class="flyout-menuItem" role="separator" data-dyn-bind="
    css: {
        'button-separator-empty': !$dyn.value($data.Label),
        'button-separator': $data.Label
    },
    visible: $data.Visible">
    <span class="menuItem-separator-label" data-dyn-bind="id: $data.Id + '_label', ariaLabelFor: $dyn.ui.ariaLabelFor($data.Id, $data, $data.Label)"></span>
</div>

<a id="HyperLink" role="link" class="hyperLink" data-dyn-bind="
    text: $data.Text,
    title: $data.Title || $data.Text,
    visible: $data.Visible,
    enabled: $data.Enabled,
    click: { callBack: $data.clicked, optOutOfAllowSave: true },
    keyDown: $data.keyDown,
    skip: $dyn.ui.skip($data),
    href: $data.href,
    superTooltip: $dyn.ui.superTooltip($data),
    sizing: $dyn.layout.sizing($data),
    target: $data.target">
</a>
<div id="Tile" tabindex="0" class="tile" role="button"
     data-dyn-bind="visible: $data.Visible,
                    enabled: $data.Enabled,
                    click: $data.Clicked,
                    keyDown: $data.keyDown,
                    focusIn: $data.focusIn,
                    focusOut: $data.focusOut,
                    sizing: $dyn.layout.sizing($data),
                    skip: $dyn.ui.skip($data),
                    superTooltip: $dyn.ui.superTooltip($data),
                    attr: { 'data-dyn-button-display': $data.buttonDisplay,
                            'tile-type': $data.TileType,
                            'data-dyn-tile-size': $data.Size }">
    <span class="tile-image" data-dyn-bind="img: $dyn.ui.img($data)"></span>
    <span class="tile-text" data-dyn-bind="id: $data.Id + '_text', labelFor: $dyn.ui.labelFor($element.parentNode, $data, $data._Label)"></span>
</div>

<a id="LinkTile" tabindex="0" class="tile" data-dyn-role-orig="Tile" role="link"
   data-dyn-bind="visible: $data.Visible,
                    enabled: $data.Enabled,
                    click: $data.Clicked,
                    keyDown: $data.keyDown,
                    focusIn: $data.focusIn,
                    sizing: $dyn.layout.sizing($data),
                    skip: $dyn.ui.skip($data),
                    href: $dyn.value($data.Url) ? $data.Url : '#',
                    target: $dyn.value($data.Url) ? '_blank' : '',
                    superTooltip: $dyn.ui.superTooltip($data),
                    attr: { 'data-dyn-button-display': $data.buttonDisplay,
                            'tile-type': $data.TileType,
                            'data-dyn-tile-size': $data.Size }">
    <span class="tile-image" data-dyn-bind="img: $dyn.ui.img($data)"></span>
    <span class="tile-text" data-dyn-bind="id: $data.Id + '_text', labelFor: $dyn.ui.labelFor($element.parentNode, $data, $data._Label)"></span>
</a>

<div id="CountTile" tabindex="0" class="tile" data-dyn-role-orig="Tile" role="button"
     data-dyn-bind="visible: $data.Visible,
                    enabled: $data.Enabled,
                    click: $data.Clicked,
                    keyDown: $data.keyDown,
                    focusIn: $data.focusIn,
                    sizing: $dyn.layout.sizing($data),
                    css: { 'hasCountAndImage': $data.hasCountAndImage,
                           'tile-isZeroCount': $dyn.value($data.Count) == 0},
                    skip: $dyn.ui.skip($data),
                    superTooltip: $dyn.ui.superTooltip($data),
                    attr: { 'data-dyn-button-display': $data.buttonDisplay,
                            'tile-type': $data.TileType,
                            'data-dyn-tile-size': $data.Size,
                            'aria-describedby': $dyn.ui.getDescribedByData($data) }">
    <span class="tileButton tile-count" data-dyn-bind="text: $data.Count"></span>
    <span class="tile-image" data-dyn-bind="img: $dyn.ui.img($data)"></span>
    <span class="tile-text" data-dyn-bind="id: $data.Id + '_text', text: $data._Label"></span>
    <span class="tile-help" data-dyn-bind="id: $data.Id + '_helptext', text: $dyn.value($data.HelpText) + ' ' + $dyn.label('CountTile_HelpText')" style="display: none; visibility: hidden;"></span>
    <div class="tile-refresh" aria-hidden="true" data-dyn-bind="flyout: $data.refreshFlyoutOptions">
        <span class="tile-refreshIcon Info-symbol"></span>
        <span class="tile-refreshHiddenLabel" 
            data-dyn-bind="text: $dyn.format('{0} {1}', $dyn.label('Framework_Tile_MoreInfo'), $dyn.label('Framework_Tile_ButtonRole'))"></span>
    </div>
    <div class="tile-refreshFlyout sysPopup">
        <p data-dyn-bind="text: $data.timeSinceTileRefreshText"></p>
        <p data-dyn-bind="text: $data.timeUntilTileRefreshText"></p>
        <a data-dyn-role="AnchorButton" data-dyn-bind="Visible: $data.isManualRefreshEnabled, Label: $data.refreshNowLabel, Click: $data.refreshNow"></a>
    </div>
</div>

<div id="KPITile" tabindex="0" class="tile kpi-tile" data-dyn-role-orig="Tile" role="button"
     data-dyn-bind="visible: $data.Visible,
                    enabled: $data.Enabled,
                    click: $data.Clicked,
                    keyDown: $data.keyDown,
                    focusIn: $data.focusIn,
                    sizing: $dyn.layout.sizing($data),
                    Status: $data.KpiStatus,
                    Trend: $data.KpiTrend,
                    Value: $data.kpiValue,
                    css: { 'kpi-count-tile': ($dyn.value($data.ShowStatus) == 'No' && $dyn.value($data.ShowGoal) == 'No') ||
                                             ($dyn.value($data.ShowStatus) == 'No' && $dyn.value($data.Size) == 'Medium')
                    },
                    skip: $dyn.ui.skip($data),
                    href: $dyn.value($data.Url) ? $data.Url : '#',
                    target: $dyn.value($data.Url) ? '_blank' : '',
                    superTooltip: $dyn.ui.superTooltip($data),
                    attr: { 'data-dyn-button-display': $data.buttonDisplay,
                            'tile-type': $data.TileType,
                            'data-dyn-tile-size': $data.Size,
                            'aria-describedby': $dyn.ui.getDescribedByData($data)}">
        <span class="tileButton kpi-summary-value-container"
          data-dyn-bind="css: {'tile-count': ($dyn.value($data.ShowStatus) == 'No' && $dyn.value($data.ShowGoal) == 'No') || ($dyn.value($data.ShowStatus) == 'No' && $dyn.value($data.Size) == 'Medium')}">
        <span class="kpi-summary-value" data-dyn-bind="text: $data.kpiValue"></span>
        <span class="kpi-summary-magnitude-indicator" data-dyn-bind="text: $data.KpiMagnitude"></span>
    </span>
    <span class="kpi-status"
          data-dyn-bind="css: {'kpiTile-businessIndicatorStatus' : $dyn.value($data.ShowStatus) == 'No',
                               'kpi-red-status': $dyn.value($data.ShowStatus) == 'Yes' && $dyn.value($data.KpiStatus) == 'Red',
                               'kpi-green-status': $dyn.value($data.ShowStatus) == 'Yes' && $dyn.value($data.KpiStatus) == 'Green',
                               'kpi-yellow-status': $dyn.value($data.ShowStatus) == 'Yes' && $dyn.value($data.KpiStatus) == 'Yellow'}">
    </span>
    <span class="kpi-trend"
          data-dyn-bind="css: {'kpiTile-businessIndicatorTrend' : $dyn.value($data.ShowTrend) == 'No',
                               'Down-symbol': $dyn.value($data.ShowTrend) == 'Yes' && $dyn.value($data.KpiTrend) == 'Down',
                               'Next-symbol': $dyn.value($data.ShowTrend) == 'Yes' && $dyn.value($data.KpiTrend) == 'Neutral',
                               'Up-symbol': $dyn.value($data.ShowTrend) == 'Yes' && $dyn.value($data.KpiTrend) == 'Up'}">
    </span>
    <span class="kpiTile-summaryGoal" data-dyn-bind="visible: $dyn.value($data.ShowGoal) == 'Yes' && $dyn.value($data.Size) == 'Wide'">
        <span class="kpiTile-summaryGoalLabelContainer">
            <span class="kpiTile-summaryGoalLabel" data-dyn-bind="text: $data.ThresholdDisplayName"></span>
        </span>
        <span class="kpiTile-summaryGoalValue"
              data-dyn-bind="text: $data.PercentageChange,
                             css: {'kpiTile-isIncreasing': $dyn.value($data.KpiStatus) == 'Green',
                                   'kpiTile-isDecreasing': $dyn.value($data.KpiStatus) == 'Red'}">
        </span>
    </span>
    <span class="tile-help" data-dyn-bind="id: $data.Id + '_helptext', text: $dyn.value($data.HelpText)" style="display: none; visibility: hidden;"></span>
    <span class="tile-text" data-dyn-bind="id: $data.Id + '_text', labelFor: $dyn.ui.labelFor($element.parentNode, $data, $data._Label)"></span>
</div>
<div id="Input" role="presentation" class="input_container layout-ignoreArrange viewContainer" data-dyn-focus=".field" data-dyn-bind="
        visible: $data.Visible,
        viewMode: $data.IsViewMode,
        enabled: $data.Enabled,
        sizing: $dyn.layout.sizing($data),
        fieldOptions: $dyn.ui.fieldOptions($data),
        css: { 'field-empty': $data.isValueEmpty, 'field-hasLookupButton': $data.LookupButton, 'lookup-flyoutOpen': $data.ShowFlyout, 'lookup-only': $data.LookupOnly },
        allowEdit: $data.AllowEdit,
        boundaryFocus: { focusOutCallBack: $data.focusOutCallBack, focusInCallBack: $data.focusInCallBack, enabled: $data.LookupButton },
        displayOptions: $data.DisplayOptions,
    ">
    <label class="label staticText boundary-focus-skip" data-dyn-bind="
           id: $data.Id + '_label',
           superTooltip: $dyn.ui.superTooltip($data),
           text: $data.Label,
           showLabel: { Label: $data.Label, ShowLabel: $data.ShowLabel },
           css: { 'showFieldHelpIcon': $dyn.ui.shouldFieldShowHelp($data) && $dyn.debug.fieldHelp }">
    </label>
    <span data-dyn-role="FieldHelpSection" data-dyn-bind="Id: $data.Id, HelpText: $data.HelpText"></span>
    <span aria-hidden="true" class="field-status fieldOptions" data-dyn-bind="title: $data.toolTip, click: $data.clickedFieldStatus, focusIn: $data.focusInput, chooseCss: { 'status': $dyn.ui.status($data) }"></span>
    <input class="textbox field displayoption viewMarker" autocomplete="off" type="text" role="textbox" data-dyn-bind="
        attr: {
            name: $data.Name,
            'aria-describedby': $dyn.ui.getDescribedByData($data),
            placeholder: $data.PlaceHolder,
            'aria-invalid': !$dyn.value($data.IsValid),
        },
        id: $data.Id + '_input',
        ariaLabelledBy: $data.getLabelledByData(),
        boundValue: { binder: $data.valueBinder, changeMode: $data.ChangeMode },
        link: $dyn.ui.link($data),
        secondaryNavigation: {keyboard: $data.OnKeyboardSecondaryNavigation, mouse: $data.OnMouseSecondaryNavigation},
        skip: $dyn.ui.skip($data),
        password: $data.PasswordMode,
        title: $data.toolTip,
        required: $data.Required,
        allowEdit: $dyn.value($data.LookupOnly) ? false :  $dyn.value($data.allowTyping),
        enabled: $data.Enabled,
        maxlength: $data.conditionalLimitTextLength,
        textAlign: $data.Alignment,
        keyDown: $data.keyDown,
        keyUp: $data.keyUp,
        input: $data.onInput,
        click: $data.onInputClick,
        preview: $dyn.ui.preview($data),
        foregroundColor: $data.ForegroundColor,
        backgroundColor: $data.BackgroundColor,
        superTooltip: $dyn.ui.superTooltip($data),
        css: { 'validationFailed': $data.IsShowingWarningIndicator }" />
    <div role="presentation" class="lookupDock-buttonContainer layout-ignoreArrange" data-dyn-bind="if: $dyn.value($data.LookupButton)">
        <div class="lookupButton" aria-hidden="true" tabindex="-1" data-dyn-bind="
            title: $dyn.label('Input_LookupTooltip'),
            superTooltip: $dyn.ui.superTooltip($data),
            attr: {'data-dyn-helptext': $dyn.label('Input_LookupHelpText')},
            flyout: { skipAria: true, focusTarget: $data.FindFocusTarget, takeFocus: $data.ShouldFlyoutTakeFocus, requestPopup: $data.showPopup, of: $data.$inputElement, show: $data.ShowFlyout, positionResize: true, highlyResponsive: true, routeMessagesToParent: true, popupId: $data.popupId}">
        </div>
    </div>
</div>

<div id="InputCell" class="input_container layout-ignoreArrange isInactiveCell" data-dyn-readonly="true" data-dyn-focus=".field" data-dyn-bind="
     visible: $data.Visible,
     sizing: $dyn.layout.sizing($data),
     displayOptions: $data.DisplayOptions,
     css: { 'field-hasLookupButton': $data.LookupButton },">
    <input class="textbox field displayoption" type="text" readonly role="textbox" tabindex="-1" data-dyn-bind="
        attr: {
            name: $data.Name,
            'aria-invalid': !$dyn.value($data.IsValid),
            'aria-label': $data.Label,
        } ,
        required: $data.Required,
        textAlign: $data.Alignment,
        title: $data.formattedValue,
        enabled: $data.Enabled,
        preview: $dyn.ui.preview($data),
        valueReadonly: $data.formattedValue," />
</div>

<div id="InputCellEditor" class="input_container layout-ignoreArrange isCellEditor" data-dyn-focus=".field" data-dyn-bind="
     visible: $data.Visible,
     sizing: $dyn.layout.sizing($data),
     displayOptions: $data.DisplayOptions,
     css: { 'field-hasLookupButton': $data.LookupButton }" >
    <input class="textbox field displayoption isCellEditor" type="text" role="textbox" data-dyn-bind="
        attr: {
            name: $data.Name,
            'aria-invalid': !$dyn.value($data.IsValid),
        } ,
        required: $data.Required,
        textAlign: $data.Alignment,
        title: $data.toolTip,
        allowEdit: $data.allowTyping,
        enabled: $data.Enabled,
        valueNow: { value: $dyn.value($data.formattedValue), setter: '_setValue' },
        onChange: $data._onChange" tabindex="-1"/>
</div>

<div id="MultilineInput" role="presentation" class="input_container multilineInput customCellHeight viewContainer" data-dyn-focus=".field" data-dyn-bind="
    visible: $data.Visible,
    viewMode: $data.IsViewMode,
    css: { 'field-empty': $data.isValueEmpty, 'field-hasLookupButton': $data.LookupButton, 'lookup-flyoutOpen': $data.ShowFlyout, 'lookup-only': $data.LookupOnly },
    sizing: $dyn.layout.sizing($data),
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical, columns: '1' },
    allowEdit: $data.AllowEdit,
    enabled: $data.Enabled,
    displayOptions: $data.DisplayOptions,
    fieldOptions: $dyn.ui.fieldOptions($data)">
    <label class="label staticText boundary-focus-skip " data-dyn-bind="
           id: $data.Id + '_label',
           text: $data.Label,
           showLabel: { Label: $data.Label, ShowLabel: $data.ShowLabel },
           superTooltip: $dyn.ui.superTooltip($data),
           css: { 'showFieldHelpIcon': $dyn.ui.shouldFieldShowHelp($data) && $dyn.debug.fieldHelp }">
    </label>
    <span data-dyn-role="FieldHelpSection" data-dyn-bind="Id: $data.Id, HelpText: $data.HelpText"></span>
    <span aria-hidden="true" class="field-status fieldOptions" data-dyn-bind="click: $data.clickedFieldStatus, focusIn: $data.focusInput, chooseCss: { 'status': $dyn.ui.status($data) }"></span>
    <textarea class="multilineInput-textArea field displayoption viewMarker" autocomplete="off" role="textbox" aria-multiline="true" data-dyn-bind="
        attr: {
            name: $data.Name,
            rows: $data.DisplayHeight,
            placeholder: $data.PlaceHolder,
            'aria-describedby': $dyn.ui.getDescribedByData($data),
            'aria-invalid': !$dyn.value($data.IsValid),
        },
        id: $data.Id + '_textArea',
        ariaLabelledBy: $data.getLabelledByData(),
        boundValue: { binder: $data.valueBinder, changeMode: $data.ChangeMode, allowEnter: true },
        link: $dyn.ui.link($data),
        secondaryNavigation: {keyboard: $data.OnKeyboardSecondaryNavigation, mouse: $data.OnMouseSecondaryNavigation},
        title: $data.toolTip,
        sizing: {height: ($dyn.value($data.Height) == $dyn.layout.Size.available ? $dyn.layout.Size.available : $dyn.layout.Size.content),
                 width: ($dyn.value($data.Width) == $dyn.layout.Size.available ? $dyn.layout.Size.available : $dyn.layout.Size.content) },
        skip: $dyn.ui.skip($data),
        required: $data.Required,
        allowEdit: $data.AllowEdit,
        enabled: $data.Enabled,
        maxlength: $data.LimitText,
        textAlign: $data.Alignment,
        keyDown: $data.keyDown,
        keyUp: $data.keyUp,
        input: $data.onInput,
        focusIn: $data.focusInCallBack,
        blur: $data.focusOutCallBack,
        foregroundColor: $data.ForegroundColor,
        backgroundColor: $data.BackgroundColor,
        css: { 'validationFailed': $data.IsShowingWarningIndicator }"></textarea>
        <div role="presentation" class="lookupDock-buttonContainer layout-ignoreArrange" data-dyn-bind="if: $dyn.value($data.ShowLookupButton)">
          <div class="lookupButton" aria-hidden="true" tabindex="-1" data-dyn-bind="
              title: $dyn.label('Input_LookupTooltip'),
              superTooltip: $dyn.ui.superTooltip($data),
              attr: {'data-dyn-helptext': $dyn.label('Input_LookupHelpText')},
              flyout: { skipAria: true, focusTarget: $data.FindFocusTarget, takeFocus: $data.ShouldFlyoutTakeFocus, requestPopup: $data.showPopup, of: $data.$inputElement, show: $data.ShowFlyout, positionResize: true, highlyResponsive: true, routeMessagesToParent: true}">
          </div>
      </div>
</div>

<div id="MultilineInputCell" class="input_container multilineInput isInactiveCell customCellHeight " data-dyn-bind="
     visible: $data.Visible,
     sizing: $dyn.layout.sizing($data),
     displayOptions: $data.DisplayOptions,
     superTooltip: $dyn.ui.superTooltip($data),
     allowEdit: $data.AllowEdit,
     css: { 'showFieldHelpIcon': $dyn.ui.shouldFieldShowHelp($data) && $dyn.debug.fieldHelp }">
    <textarea class="multilineInput-textArea field displayoption" role="textbox" readonly aria-multiline="true" tabindex="-1" data-dyn-bind="
        attr: {
            name: $data.Name,
            rows: $data.DisplayHeight,
            'aria-invalid': !$dyn.value($data.IsValid),
            'aria-label': $data.Label,
       },
        required: $data.Required,
        textAlign: $data.Alignment,
        enabled: $data.Enabled,
        title: $data.formattedValue,
        text: $data.formattedValue">
    </textarea>
</div>

<div id="MultilineInputCellEditor" class="input_container multilineInput layout-ignoreArrange isCellEditor" data-dyn-focus=".field" data-dyn-bind="
     visible: $data.Visible,
     sizing: $dyn.layout.sizing($data),
     displayOptions: $data.DisplayOptions,
     css: { 'field-hasLookupButton': $data.LookupButton }">
    <textarea class="multilineInput-textArea field displayoption isCellEditor" type="text" role="textbox" data-dyn-bind="
        attr: {
            name: $data.Name,
            rows: $data.DisplayHeight,
            'aria-invalid': !$dyn.value($data.IsValid),
            'aria-label': $data.Label,
        },
        required: $data.Required,
        textAlign: $data.Alignment,
        title: $data.toolTip,
        allowEdit: $data.allowTyping,
        enabled: $data.Enabled,
        valueNow: { value: $dyn.value($data.formattedValue), setter: '_setValue' },
        onChange: $data._onChange" tabindex="-1">
    </textarea>
</div>

<div id="DateTime" role="presentation" class="input_container layout-reflow-scope viewContainer" data-dyn-focus=".field" data-dyn-bind="
    visible: $data.Visible,
    viewMode: $data.IsViewMode,
    css: { 'field-empty': $data.isValueEmpty, 'field-hasLookupButton': $data.LookupButton },
    attr: { 'data-dynamics-datetime-timezoneindicator': $data.ShowTimeZoneIndicator },
    sizing: $dyn.layout.sizing($data),
    allowEdit: $data.AllowEdit,
    enabled: $data.Enabled,
    displayOptions: $data.DisplayOptions,
    fieldOptions: $dyn.ui.fieldOptions($data),">
    <label class="label staticText boundary-focus-skip " data-dyn-bind="
               id: $data.Id + '_label',
               text: $data.Label,
               showLabel: { Label: $data.Label, ShowLabel: $data.ShowLabel },
               superTooltip: $dyn.ui.superTooltip($data),
               css: { 'showFieldHelpIcon': $dyn.ui.shouldFieldShowHelp($data) && $dyn.debug.fieldHelp }">
    </label>
    <div class="lookupDock-dockContainer lookupDock-dateTime displayoption" data-dyn-bind="
        boundaryFocus: { focusOutCallBack: $data.focusOutCallBack, focusInCallBack: $data.focusInCallBack, showFlyout: $data.ShowFlyout, enabled: $data.LookupButton },
        css: { 'hasFocusedChild': $data.isFocused() || $data.pickerOpen(), 'statusMandatory': $data.IsShowingMandatoryIndicator, 'statusWarning': $data.IsShowingWarningIndicator },
        allowEdit: $data.AllowEdit,
        enabled: $data.Enabled">
        <div class="lookupDock-contentContainer displayoption" data-dyn-bind="
                ariaLabelledBy: $data.getLabelledByData()">
            <span class="timeZoneIndicator Timer-symbol" data-dynamics-imagetype="Symbol" data-dyn-bind="
                visible: $data.ShowTimeZoneIndicator,
                title: $data.TimeZoneName,"></span>
            <span data-dyn-role="FieldHelpSection" data-dyn-bind="Id: $data.Id, HelpText: $data.HelpText"></span>
            <span aria-hidden="true" class="field-status fieldOptions" data-dyn-bind="title: $data.toolTip, click: $data.clickedFieldStatus, focusIn: $data.focusInput, chooseCss: { 'status': $dyn.ui.status($data) }"></span>
            <input class="textbox field displayoption viewMarker" type="text" role="textbox" autocomplete="off" data-dyn-bind="
            attr: {
                name: $data.Name,
                placeholder: $data.PlaceHolder,
                'aria-describedby': $dyn.ui.getDescribedByData($data),
                'aria-invalid': !$dyn.value($data.IsValid),
            },
            id: $data.Id + '_input',
            ariaLabelledBy: $data.getLabelledByData(),
            required: $data.Required,
            boundValue: { binder: $data.valueBinder, changeMode: $data.ChangeMode },
            link: $dyn.ui.link($data),
            secondaryNavigation: {keyboard: $data.OnKeyboardSecondaryNavigation, mouse: $data.OnMouseSecondaryNavigation},
            title: $data.toolTip,
            skip: $dyn.ui.skip($data),
            allowEdit: $data.AllowEdit,
            enabled: $data.Enabled,
            textAlign: $data.Alignment,
            keyDown: $data.keyDown,
            keyUp: $data.keyUp,
            input: $data.onInput,
            preview: $dyn.ui.preview($data),
            foregroundColor: $data.ForegroundColor,
            backgroundColor: $data.BackgroundColor,
            css: { 'validationFailed': $data.IsShowingWarningIndicator },
            superTooltip: $dyn.ui.superTooltip($data)," />
        </div>
        <div role="presentation" class="lookupDock-buttonContainer layout-ignoreArrange" data-dyn-bind="if: ($dyn.value($data.LookupButton) && !$dyn.value($data.CanOpenLookupForm))">
            <div class="lookupButton" aria-hidden="true" tabindex="-1" data-dyn-bind="
                click: $data.showPicker,
                mouseDown: $data.checkPickerState,
                title: $dyn.label('Input_LookupTooltip'),
                superTooltip: $dyn.ui.superTooltip($data),
                attr: {'data-dyn-helptext': $dyn.label('Input_LookupHelpText')} ">
            </div>
        </div>
        <div role="presentation" class="lookupDock-buttonContainer layout-ignoreArrange" data-dyn-bind="if: ($dyn.value($data.LookupButton) && $dyn.value($data.CanOpenLookupForm))">
            <div class="lookupButton" aria-hidden="true" tabindex="-1" data-dyn-bind="
                flyout: { skipAria: true, focusTarget: $data.FindFocusTarget, takeFocus: $data.ShouldFlyoutTakeFocus, requestPopup: $data.showPopup, of: $data.$inputElement,
                          show: $data.ShowFlyout, positionResize: true, highlyResponsive: true, routeMessagesToParent: true }">
            </div>
        </div>
    </div>
</div>

<div id="Time" role="presentation" class="input_container editMode layout-ignoreArrange viewContainer" data-dyn-focus=".field" data-dyn-bind="
    visible: $data.Visible,
    sizing: $dyn.layout.sizing($data),
    viewMode: $data.IsViewMode,
    allowEdit: $data.AllowEdit,
    enabled: $data.Enabled,
    displayOptions: $data.DisplayOptions,
    fieldOptions: $dyn.ui.fieldOptions($data),">
    <label class="label staticText boundary-focus-skip  " data-dyn-bind="
           id: $data.Id + '_label',
           text: $data.Label,
           showLabel: { Label: $data.Label, ShowLabel: $data.ShowLabel },
           superTooltip: $dyn.ui.superTooltip($data),
           css: { 'showFieldHelpIcon': $dyn.ui.shouldFieldShowHelp($data) && $dyn.debug.fieldHelp }">
    </label>
    <span data-dyn-role="FieldHelpSection" data-dyn-bind="Id: $data.Id, HelpText: $data.HelpText"></span>
    <span aria-hidden="true" class="field-status fieldOptions" data-dyn-bind="title: $data.toolTip, click: $data.clickedFieldStatus, focusIn: $data.focusInput, chooseCss: { 'status': $dyn.ui.status($data) }"></span>
    <input class="textbox field allowTextSelection displayoption viewMarker" role="textbox" data-dynamics-input-alignment="Left" tabindex="0" type="text" autocomplete="off" data-dyn-bind="
        attr: {
            name: $data.Name,
            placeholder: $data.PlaceHolder,
            'aria-describedby': $dyn.ui.getDescribedByData($data),
            'aria-invalid': !$dyn.value($data.IsValid),
        },
        id: $data.Id + '_input',
        ariaLabelledBy: $data.getLabelledByData(),
        required: $data.Required,
        boundValue: { binder: $data.valueBinder, changeMode: $data.ChangeMode },
        link: $dyn.ui.link($data),
        secondaryNavigation: {keyboard: $data.OnKeyboardSecondaryNavigation, mouse: $data.OnMouseSecondaryNavigation},
        title: $data.toolTip,
        skip: $dyn.ui.skip($data),
        allowEdit: $data.AllowEdit,
        enabled: $data.Enabled,
        textAlign: $data.Alignment,
        keyDown: $data.keyDown,
        keyUp: $data.keyUp,
        input: $data.onInput,
        focusIn: $data.focusInCallBack,
        blur: $data.focusOutCallBack,
        foregroundColor: $data.ForegroundColor,
        backgroundColor: $data.BackgroundColor,
        preview: $dyn.ui.preview($data),
        css: { 'validationFailed': $data.IsShowingWarningIndicator }" />
</div>

<div id="Number" role="presentation" class="input_container number layout-ignoreArrange viewContainer" data-dyn-focus=".field" data-dyn-bind="
    visible: $data.Visible,
    viewMode: $data.IsViewMode,
    sizing: $dyn.layout.sizing($data),
    css: { 'field-hasLookupButton': $data.LookupButton, 'lookup-flyoutOpen': $data.ShowFlyout },
    allowEdit: $data.AllowEdit,
    enabled: $data.Enabled,
    boundaryFocus: { focusOutCallBack: $data.focusOutCallBack, focusInCallBack: $data.focusInCallBack, enabled: $data.LookupButton },
    displayOptions: $data.DisplayOptions,
    fieldOptions: $dyn.ui.fieldOptions($data)," >
    <label class="label staticText boundary-focus-skip " data-dyn-bind="
           id: $data.Id + '_label',
           text: $data.Label,
           showLabel: { Label: $data.Label, ShowLabel: $data.ShowLabel },
           superTooltip: $dyn.ui.superTooltip($data),
           css: { 'showFieldHelpIcon': $dyn.ui.shouldFieldShowHelp($data) && $dyn.debug.fieldHelp }">
    </label>
    <span data-dyn-role="FieldHelpSection" data-dyn-bind="Id: $data.Id, HelpText: $data.HelpText"></span>
    <span aria-hidden="true" class="field-status fieldOptions" data-dyn-bind="title: $data.toolTip, click: $data.clickedFieldStatus, focusIn: $data.focusInput, chooseCss: { 'status': $dyn.ui.status($data) }"></span>
    <input class="textbox field displayoption viewMarker" type="text" role="textbox" autocomplete="off" dir="ltr" data-dyn-bind="
        attr: {
            name: $data.Name,
            placeholder: $data.PlaceHolder,
            'aria-describedby': $dyn.ui.getDescribedByData($data),
            'aria-invalid': !$dyn.value($data.IsValid),
        },
        id: $data.Id + '_input',
        ariaLabelledBy: $data.getLabelledByData(),
        boundValue: { binder: $data.valueBinder, changeMode: $data.ChangeMode },
        link: $dyn.ui.link($data),
        secondaryNavigation: {keyboard: $data.OnKeyboardSecondaryNavigation, mouse: $data.OnMouseSecondaryNavigation},
        title: $data.toolTip,
        skip: $dyn.ui.skip($data),
        required: $data.Required,
        allowEdit: $data.AllowEdit,
        enabled: $data.Enabled,
        maxlength: $data.LimitText,
        textAlign: $data.Alignment,
        keyDown: $data.keyDown,
        keyUp: $data.keyUp,
        input: $data.onInput,
        preview: $dyn.ui.preview($data),
        foregroundColor: $data.ForegroundColor,
        backgroundColor: $data.BackgroundColor,
        css: { 'validationFailed': $data.IsShowingWarningIndicator },
        superTooltip: $dyn.ui.superTooltip($data)," />
    <div role="presentation" class="lookupDock-buttonContainer layout-ignoreArrange" data-dyn-bind="if: $dyn.value($data.LookupButton)">
        <div class="lookupButton" aria-hidden="true" tabindex="-1" data-dyn-bind="
             title: $dyn.label('Input_LookupTooltip'),
             superTooltip: $dyn.ui.superTooltip($data),
             attr: {'data-dyn-helptext': $dyn.label('Input_LookupHelpText')},
             flyout: { skipAria: true, focusTarget: $data.FindFocusTarget, requestPopup: $data.showPopup, takeFocus: $data.ShouldFlyoutTakeFocus, of: $data.$inputElement, show: $data.ShowFlyout, positionResize: true, highlyResponsive: true, routeMessagesToParent: true}">
        </div>
    </div>
</div>

<div id="NumberCell" class="input_container number layout-ignoreArrange isInactiveCell" data-dyn-readonly="true" data-dyn-focus=".field" data-dyn-bind="
     visible: $data.Visible,
     sizing: $dyn.layout.sizing($data),
     displayOptions: $data.DisplayOptions,
     css: { 'field-hasLookupButton': $data.LookupButton },">
    <input class="textbox field displayoption" type="text" readonly role="textbox" tabindex="-1" dir="ltr" data-dyn-bind="
        attr: {
            name: $data.Name,
            'aria-invalid': !$dyn.value($data.IsValid),
            'aria-label': $data.Label,
        },
        required: $data.Required,
        textAlign: $data.Alignment,
        title: $data.formattedValue,
        enabled: $data.Enabled,
        preview: $dyn.ui.preview($data),
        valueReadonly: $data.formattedValue">
</div>

<div id="NumberCellEditor" class="input_container number layout-ignoreArrange isCellEditor" dir="ltr" data-dyn-focus=".field" data-dyn-bind="
     visible: $data.Visible,
     sizing: $dyn.layout.sizing($data),
     displayOptions: $data.DisplayOptions,
     css: { 'field-hasLookupButton': $data.LookupButton }," >
    <input class="field displayoption" type="text" role="textbox" data-dyn-bind="
        attr: {
            name: $data.Name,
            'aria-invalid': !$dyn.value($data.IsValid),
            'aria-label': $data.Label,
        },
        required: $data.Required,
        textAlign: $data.Alignment,
        title: $data.formattedValue,
        allowEdit: $data.allowTyping,
        enabled: $data.Enabled,
        valueNow: { value: $dyn.value($data.formattedValue), setter: '_setValue' },
        onChange: $data._onChange" tabindex="-1">
</div>

<label id="CheckBox" class="checkBox-container layout-ignoreArrange displayoption viewContainer" data-dyn-focus=".checkBox" data-dyn-bind="
    enabled: $data.Enabled,
    allowEdit: $data.AllowEdit,
    visible: $data.Visible,
    sizing: $dyn.layout.sizing($data),
    preview: $dyn.ui.preview($data),
    focusIn: $data.focusInCallBack,
    focusOut: $data.focusOutCallBack,
    css: { 'hasFocus' : $data.isFocused() },
    chooseCss: { 'style': $dyn.ui.checkBoxStyle($data) },
    keyDown: $data.keyDown,
    displayOptions: $data.DisplayOptions,">
    <span class="checkBox" role="checkbox" tabindex="0" data-dyn-bind="
        ariaEnabled : $data.Enabled && $data.AllowEdit,
        allowEdit: $data.AllowEdit,
        click: $data.clickHandler,
        skip: $dyn.ui.skip($data),
        checked: $data.formattedValue,
        id: $data.Id + '_check',
        ariaLabelledBy: { byElementId: $data.Id + '_label', showLabel: $data.ShowLabel, isInGrid: $data._isInGrid },
        attr: {
            'aria-describedby': $dyn.ui.getDescribedByData($data),
        }"></span>
    <label class="staticText label checkBox-label" data-dyn-bind="
           id: $data.Id + '_label',
           text: $data.Label,
           showLabel: { Label: $data.Label, ShowLabel: $data.ShowLabel },
           superTooltip: $dyn.ui.superTooltip($data),
           click: function (evt) { if ($data.IsStandard) { $data.toggleValue(evt); } },
           css: { 'showFieldHelpIcon': $dyn.ui.shouldFieldShowHelp($data) && $dyn.debug.fieldHelp } ">
    </label>
    <span aria-hidden="true" class="field-status fieldOptions" data-dyn-bind="title: $data.toolTip, click: $data.clickedFieldStatus, focusIn: $data.focusInput, chooseCss: { 'status': $dyn.ui.status($data) }"></span>
    <span data-dyn-role="FieldHelpSection" data-dyn-bind="Id: $data.Id, HelpText: $data.HelpText"></span>
    <div role="presentation" class="field">
        <span class="toggle-box" role="switch" data-dyn-bind="
            ariaEnabled : $data.Enabled,
            allowEdit: $data.AllowEdit,
            click: $data.clickHandler,
            skip: $dyn.ui.skip($data),
            checked: $data.formattedValue,
            id: $data.Id + '_toggle',
            ariaLabelledBy: { byElementId: $data.Id + '_label', showLabel: $data.ShowLabel, isInGrid: $data._isInGrid },
            attr: {
                'aria-describedby': $dyn.ui.getDescribedByData($data),
            }">
            <span class="toggle-thumb"></span>
        </span>
        <span class="toggle-value" data-dyn-bind="text: $data.YesNoText, title: $data.YesNoText, superTooltip: $dyn.ui.superTooltip($data), attr: {'aria-describedby': $dyn.ui.getDescribedByData($data) },"></span>
    </div>
</label>

<div id="CheckBoxCell" class="checkBox-container layout-ignoreArrange displayoption isInactiveCell" data-dyn-readonly="true" data-dyn-focus=".checkBox" data-dyn-bind="
     visible: $data.Visible,
     sizing: $dyn.layout.sizing($data),
     chooseCss: { 'style': $dyn.ui.checkBoxStyle($data) },
     onKeyDown: $data.keyDown,
     preview: $dyn.ui.preview($data),
     displayOptions: $data.DisplayOptions,
     enabled: $data.Enabled">
    <div role="presentation" class="field">
        <span class="checkBox" role="checkbox" data-dyn-bind="checked: $data.formattedValue, onClick: $data.toggleValueForCell, attr: {'aria-label': $data.Label} " tabindex="-1"></span>
        <span class="toggle-value" data-dyn-bind="text: $data.YesNoText"></span>
    </div>
</div>

<div id="ReferenceGroup" class="referenceGroup field-hasLookupButton layout-reflow-scope viewContainer" data-dyn-container=".lookupDock-contentContainer" data-dyn-focus=".field" data-dyn-bind="
     enabled: $data.Enabled,
     allowEdit: $data.AllowEdit,
     visible: $data.Visible,
     viewMode: $data.IsViewMode,
     sizing: $dyn.layout.sizing($data),
     layout: { arrangeMethod: $value($data.Width) == $dyn.layout.Size.available ? $dyn.layout.ArrangeMethod.vertical : $dyn.layout.ArrangeMethod.none },
     ariaLabelledBy: { byElementId: $data.Id + '_label', showLabel: $data.ShowLabel, isInGrid: $data._isInGrid },
     displayOptions: $data.DisplayOptions,">
    <label class="lookup-label label " data-dyn-bind="
            id: $data.Id + '_label',
            text: $data.Label,
            showLabel: { Label: $data.Label, ShowLabel: $data.ShowLabel },
            superTooltip: $dyn.ui.superTooltip($data),
            css: { 'showFieldHelpIcon': $dyn.ui.shouldFieldShowHelp($data) && $dyn.debug.fieldHelp }">
    </label>
    <div class="lookupDock lookupDock-dockContainer displayoption" data-dyn-bind="
        allowEdit: $data.AllowEdit,
        keyDown: $data.keyDown,
        boundaryFocus: { focusOutCallBack: $data.focusOutCallBack, focusInCallBack: $data.focusInCallBack, enabled: $data.LookupButton },
        css: {
            'hasFocusedChild': $data.isFocused,
            'statusMandatory': $data.IsShowingMandatoryIndicator,
            'statusWarning': $data.IsShowingWarningIndicator,
            },
        sizing: $dyn.layout.sizing($data),
        foregroundColor: $data.ForegroundColor,
        backgroundColor: $data.BackgroundColor,
        layout: { arrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft }">
        <div class="lookupDock-contentContainer" data-dyn-content="append: '*'" data-dyn-bind="
             layout: { arrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft },
             sizing: { width: $dyn.layout.Size.available }">
        </div>
        <div role="presentation" class="lookupDock-buttonContainer layout-ignoreArrange">
            <div class="lookupButton" aria-hidden="true" tabindex="-1" data-dyn-bind="
                 title: $dyn.label('Input_LookupTooltip'),
                 superTooltip: $dyn.ui.superTooltip($data),
                 attr: {'data-dyn-helptext': $dyn.label('Input_LookupHelpText')},
                 flyout: { skipAria: true, focusTarget: $data.FindFocusTarget, requestPopup: $data.showPopup, takeFocus: $data.ShouldFlyoutTakeFocus,
                    clickSubscriber: $data.flyoutClickSubscriber, of: $($element).closest('.lookupDock'), show: $data.ShowFlyout, positionResize: true, highlyResponsive: true, routeMessagesToParent: true}">
            </div>
        </div>
    </div>
</div>

<div id="ReferenceGroupCell" class="referenceGroup field-hasLookupButton layout-reflow-scope isInactiveCell" data-dyn-readonly="true" data-dyn-container=".lookupDock-contentContainer" data-dyn-bind="
     visible: $data.Visible,
     sizing: $dyn.layout.sizing($data),
     layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
     displayOptions: $data.DisplayOptions,">
    <div class="lookupDock lookupDock-dockContainer displayoption" data-dyn-readonly="true" data-dyn-bind="
         sizing: { width: $dyn.layout.Size.available },
         layout: { arrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft }">
        <div class="lookupDock-contentContainer" data-dyn-content="append: '*'" data-dyn-bind="
             layout: { arrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft },
             sizing: { width: $dyn.layout.Size.available }">
        </div>
    </div>
</div>

<div id="ComboBox" role="presentation" class="input_container field-hasLookupButton layout-reflow-scope comboBox viewContainer" data-dyn-focus=".field" data-dyn-bind="
    visible: $data.Visible,
    viewMode: $data.IsViewMode,
    sizing: $dyn.layout.sizing($data),
    allowEdit: $data.AllowEdit,
    enabled: $data.Enabled,
    dynValue: $dyn.value($data.Items) ? $data.SelectedItem : null,
    displayOptions: $data.DisplayOptions,
    fieldOptions: $dyn.ui.fieldOptions($data),
    boundaryFocus: { focusInCallBack: $data.focusInCallBack, focusOutCallBack: $data.focusOutCallBack, enabled: true },">
    <label class="label staticText " data-dyn-bind="
           id: $data.Id + '_label',
           text: $data.Label,
           showLabel: { Label: $data.Label, ShowLabel: $data.ShowLabel },
           superTooltip: $dyn.ui.superTooltip($data),
           css: { 'showFieldHelpIcon': $dyn.ui.shouldFieldShowHelp($data) && $dyn.debug.fieldHelp }">
    </label>
    <div class="lookupDock-dockContainer lookupDock-comboBox displayoption" data-dyn-bind="
        allowEdit: $data.AllowEdit,
        enabled: $data.Enabled,
        css: { 'hasFocusedChild': $data.isFocused() || $data.isExpanded(), 'statusMandatory': $data.IsShowingMandatoryIndicator, 'statusWarning': $data.IsShowingWarningIndicator },">
        <div class="lookupDock-contentContainer displayoption" data-dyn-bind="
            attr: $dyn.value($data.ComboboxTypeAheadFeature) ? { role: $dyn.value($data.ComboboxTypeAheadFeature) ? 'presentation' : 'combobox' } : {
                'aria-owns': $data.Id + '_list',
                'aria-expanded': $dyn.value($data.isExpanded),
                'aria-haspopup': 'listbox',
                role: $dyn.value($data.ComboboxTypeAheadFeature) ? 'presentation' : 'combobox',
            }">
            <span data-dyn-role="FieldHelpSection" data-dyn-bind="Id: $data.Id, HelpText: $data.HelpText"></span>
            <span aria-hidden="true" class="field-status fieldOptions" data-dyn-bind="title: $data.toolTip, click: $data.clickedFieldStatus, focusIn: $data.focusInput, chooseCss: { 'status': $dyn.ui.status($data) }"></span>
            <input class="textbox field displayoption viewMarker" type="text" aria-autocomplete="list" data-dyn-bind="
                attr: $dyn.value($data.ComboboxTypeAheadFeature) ? {
                    name: $data.Name,
                    'aria-invalid': !$dyn.value($data.IsValid),
                    'aria-controls': $data.Id + '_list',
                    'aria-describedby': $dyn.ui.getDescribedByData($data),
                    'aria-expanded': $dyn.value($data.isExpanded),
                    'aria-haspopup': 'listbox',
                    role: $dyn.value($data.ComboboxTypeAheadFeature) ? 'combobox' : 'textbox',
                } : {
                    name: $data.Name,
                    'aria-invalid': !$dyn.value($data.IsValid),
                    'aria-controls': $data.Id + '_list',
                    'aria-describedby': $dyn.ui.getDescribedByData($data),
                    'data-dyn-readonly': true,
                    role: $dyn.value($data.ComboboxTypeAheadFeature) ? 'combobox' : 'textbox',
                },
                ariaLabelledBy: { byElementId: $data.Id + '_label', showLabel: $data.ShowLabel, isInGrid: $data._isInGrid },
                required: $data.Required,
                enabled: $data.Enabled,
                id: $data.Id + '_input',
                valueReadonly: $data.selectedLabel(),
                textAlign: $data.Alignment,
                skip: $dyn.ui.skip($data),
                title: $data.selectedLabel(),
                blur: $data.blur,
                keyDown: $data.onKeyDown,
                foregroundColor: $data.ForegroundColor,
                preview: $dyn.ui.preview($data),
                backgroundColor: $data.BackgroundColor,
                typeToAutoComplete: { visible: $data.Visible, enabled: $data.Enabled, filteredItems: $data.filteredItems, selectedIndex: $data.selectedIndex, shownIndex: $data.shownIndex, items: $data.Items, allowEdit: $data.AllowEdit, skipCollapsedSelection: $data.skipCollapsedSelection, expanded: $data.isExpanded, listShownIndex: $data.listShownIndex },
                typeToSelect: { selectedIndex: $data.selectedIndex, shownIndex: $data.shownIndex, items: $dyn.value($data.Items), allowEdit: $data.AllowEdit, skipCollapsedSelection: $data.skipCollapsedSelection, expanded: $data.isExpanded, listShownIndex: $data.listShownIndex, checkFeature: true },
                click: $data.onInputClick,
                css: { 'validationFailed': $data.IsShowingWarningIndicator },
                superTooltip: $dyn.ui.superTooltip($data)," />
            <ul class="comboBox-list sysPopup" tabindex="-1" role="listbox" data-dyn-bind="
                id: $data.Id + '_list',
                ariaLabelledBy: { byElementId: $data.Id + '_label', showLabel: $data.ShowLabel, isInGrid: $data._isInGrid },
                attr: {
                    'aria-hidden': !$dyn.value($data.isExpanded),
                },
                foreach: { collection: $dyn.value($data.ComboboxTypeAheadFeature) ? $data.filteredItems : $data.Items, setAriaAttributes: false }">
                <li role="option" data-dyn-bind="
                    id: $parent().Id + '_list_item' + $index,
                    text: $data.Label,
                    showLabel: { Label: $data.Label, AllowBlankLabel: true },
                    superTooltip: $dyn.ui.superTooltip($data),
                    attr: {
                        'aria-selected': $dyn.value($parent().listShownIndex) == $index,
                    },
                    click: { callBack: function () { $parent().clickedItem($index); }, stopPropagation: true }">
                </li>
            </ul>
        </div>
        <div role="presentation" class="lookupDock-buttonContainer layout-ignoreArrange">
            <div class="lookupButton" aria-hidden="true" tabindex="-1" data-dyn-bind="
                 title: $dyn.label('Input_LookupTooltip'),
                 superTooltip: $dyn.ui.superTooltip($data),
                 attr: {'data-dyn-helptext': $dyn.label('Input_LookupHelpText')},
                 flyout: { skipAria: true, flyout: $($element).parent().parent().find('.comboBox-list'), of: $($element).parent().parent(), show: $data.isExpanded, positionResize: true,
                           takeFocus: false, clickSubscriber: $data.flyoutClickSubscriber, optOutOfWait: true, escapeSubscriber: $dyn.value($data.ComboboxTypeAheadFeature) ? $data.flyoutEscapeSubscriber : $dyn.util.flyout.defaultFlyoutEscapeSubscriber }">
            </div>
        </div>
    </div>
</div>

<ul id="ComboBoxPopup" class="comboBox-list sysPopup" tabindex="-1" role="list" data-dyn-bind="foreach: $data.Items" style="display: none">
    <li role="listitem" data-dyn-bind="
                    valueReadonly: $data.Value,
                    label: $data.Label,
                    selected: $dyn.value($parent().shownItem) == $dyn.value($data.Value),
                    attr: {
                        'aria-posinset': $index + 1,
                        'aria-setsize': $length,
                    }">
        <a data-dyn-bind="
                        text: $data.Label,
                        showLabel: { Label: $data.Label, AllowBlankLabel: true },
                        click: {callBack: function () { $parent().clickedItem($index); }, stopPropagation: true} ">
        </a>
    </li>
</ul>

<div id="ComboBoxCell" class="input_container field-hasLookupButton layout-ignoreArrange isInactiveCell" data-dyn-readonly="true" data-dyn-focus=".field" data-dyn-bind="
     visible: $data.Visible,
     sizing: $dyn.layout.sizing($data),
     displayOptions: $data.DisplayOptions,
     dynValue: $data.SelectedItem">
    <input class="textbox field displayoption" readonly type="text" role="textbox" tabindex="-1" data-dyn-bind="
        attr: {
            name: $data.Name,
            'aria-invalid': !$dyn.value($data.IsValid),
            'aria-label': $data.Label,
        },
        enumAriaItems: $data.Items,
        enumAriaSelection: $data.selectedIndex,
        textAlign: $data.Alignment,
        title: $data.formattedValue,
        enabled: $data.Enabled,
        ariaValueNow: $data.SelectedItem,
        valueReadonly: $data.formattedValue,
        preview: $dyn.ui.preview($data)" />
</div>

<div id="ComboBoxCellEditor" class="input_container field-hasLookupButton layout-reflow-scope comboBox isCellEditor" data-dyn-focus=".field" data-dyn-bind="
    visible: $data.Visible,
    viewMode: $data.IsViewMode,
    sizing: $dyn.layout.sizing($data),
    preview: $dyn.ui.preview($data),
    enabled: $data.Enabled,
    dynValue: $dyn.value($data.Items) ? $data.SelectedItem : null,
    displayOptions: $data.DisplayOptions" >
    <div class="lookupDock-dockContainer lookupDock-comboBox displayoption" data-dyn-bind="
        allowEdit: $data.AllowEdit,
        enabled: $data.Enabled,
        css: { 'hasFocusedChild': $data.isFocused() || $data.isExpanded() }">
        <div class="lookupDock-contentContainer displayoption" role="combobox" data-dyn-bind="
             attr: {
                    'aria-owns': $data.Id + '_list',
                    'aria-expanded': $dyn.value($data.isExpanded),
                    'aria-haspopup': 'listbox'
                }">
            <span data-dyn-role="FieldHelpSection" data-dyn-bind="Id: $data.Id, HelpText: $data.HelpText"></span>
            <span aria-hidden="true" class="field-status fieldOptions" data-dyn-bind="title: $data.toolTip, click: $data.clickedFieldStatus, focusIn: $data.focusInput, chooseCss: { 'status': $dyn.ui.status($data) }"></span>
            <input class="textbox field displayoption" tabindex="-1" type="text" role="textbox" aria-haspopup="true" aria-autocomplete="list" readonly="readonly" data-dyn-bind="
                attr: {
                     name: $data.Name,
                    'aria-invalid': !$dyn.value($data.IsValid),
                    'aria-controls': $data.Id + '_list',
                    'aria-describedby': $dyn.ui.getDescribedByData($data),
                    'aria-label': $data.Label,
                },
                enumAriaItems: $data.Items,
                enumAriaSelection: $data.selectedIndex,
                enabled: $data.Enabled,
                required: $data.Required,
                valueReadonly: $data.selectedLabel(),
                textAlign: $data.Alignment,
                title: $data.selectedLabel(),
                keyDown: $data.onKeyDown,
                onTypeToSelect: { selectedIndex: $data.selectedIndex, shownIndex: $data.shownIndex, items: $dyn.value($data.Items), allowEdit: $data.AllowEdit, expanded: $data.isExpanded },
                click: $data.onInputClick,
                ariaValueNow: $dyn.value($data.Items) ? $data.SelectedItem : null" />
        </div>
        <div role="presentation" class="lookupDock-buttonContainer layout-ignoreArrange">
            <div class="lookupButton" aria-hidden="true" tabindex="-1" data-dyn-bind="
                 title: $dyn.label('Input_LookupTooltip'),
                 superTooltip: $dyn.ui.superTooltip($data),
                 attr: {'data-dyn-helptext': $dyn.label('Input_LookupHelpText')},
                 onFlyout: { requestPopup: $data._requestPopup.bind($data), of: $($element).parent().parent(), show: $data.isExpanded, positionResize: true,
                             takeFocus: false, clickSubscriber: $data.flyoutClickSubscriber, optOutOfWait: true }">
            </div>
        </div>
    </div>
</div>

<div id="ListBox" role="presentation" class="input_container listbox viewContainer" data-dyn-focus=".listbox-list" data-dyn-bind="
    visible: $data.Visible,
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
    sizing: $dyn.layout.sizing($data),
    preview: $dyn.ui.preview($data)">
    <label class="label staticText " data-dyn-bind="
           id: $data.Id + '_label',
           text: $data.Label,
           showLabel: { Label: $data.Label, ShowLabel: $data.ShowLabel },
           superTooltip: $dyn.ui.superTooltip($data),
           css: { 'showFieldHelpIcon': $dyn.ui.shouldFieldShowHelp($data) && $dyn.debug.fieldHelp } ">
    </label>
    <span data-dyn-role="FieldHelpSection" data-dyn-bind="Id: $data.Id, HelpText: $data.HelpText"></span>
    <span aria-hidden="true" class="field-status fieldOptions" data-dyn-bind="chooseCss: { 'status': $dyn.ui.status($data) }"></span>
    <ul class="listbox-list" role="listbox" data-dyn-bind="
        attr: {
            'aria-describedby': $dyn.ui.getDescribedByData($data),
            'aria-activedescendant': $data.Id + '_item_' + $dyn.value($data.selectedIndex),
        },
        ariaLabelledBy: { byElementId: $data.Id + '_label', showLabel: $data.ShowLabel, isInGrid: $data._isInGrid },
        id: $data.Id + '_list',
        allowEdit: $data.AllowEdit,
        enabled: $data.Enabled,
        foreach: { collection: $data.Items, setAriaAttributes: false },
        typeToSelect: { selectedIndex: $data.selectedIndex, shownIndex: $data.shownIndex, items: $dyn.value($data.Items), allowEdit: $dyn.value($data.AllowEdit), checkFeature: false },
        skip: $dyn.ui.skip($data),
        backgroundColor: $data.BackgroundColor,
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available },
        css: { 'defaultHeight': $dyn.value($data.Height) == $dyn.layout.Size.content || $dyn.value($data.Height) == $dyn.ui.autoValue }, /* Review auto value handling */">
        <li role="option" data-dyn-bind="
            valueReadonly: $data.Value,
            text: $data.Label,
            showLabel: { Label: $data.Label, AllowBlankLabel: true },
            id: $parent().Id + '_item_' + $index,
            superTooltip: $dyn.ui.superTooltip($data),
            selected: $dyn.value($parent().shownItem) == $dyn.value($data.Value),
            sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.content },
            click: function () { $parent().selectedIndex($index); },
            foregroundColor: $parent().ForegroundColor">
        </li>
    </ul>
</div>

<div id="RadioButton" class="radioButton-container" role="radiogroup" data-dyn-focus="[aria-checked='true']" data-dyn-bind="
    visible: $data.Visible,
    sizing: $dyn.layout.sizing($data),
    preview: $dyn.ui.preview($data),
    focusIn: $data.focusInCallBack,
    focusOut: $data.focusOutCallBack,
    ariaLabelledBy: { byElementId: $data.Id + '_title', showLabel: $data.ShowLabel, isInGrid: $data._isInGrid }">
    <span class="staticText group_title" data-dyn-bind="
            id: $data.Id + '_title',
            text: $data.Label,
            showLabel: { Label: $data.Label, ShowLabel: $data.ShowLabel },
            superTooltip: $dyn.ui.superTooltip($data),
            css: { 'showFieldHelpIcon': $dyn.ui.shouldFieldShowHelp($data) && $dyn.debug.fieldHelp } ">
    </span>
    <div data-dyn-bind="
        foreach: { collection: $data.Items, preRender: $data.preRenderCallBack, postRender: $data.postRenderCallBack, setAriaAttributes: false },
        layout: $dyn.layout.radioButtonBinding($data)">
        <div class="radioButton">
            <input type="radio" role="radio" data-dyn-bind="
                id: $parent().Id + '_option_' + $index,
                checked: $dyn.value($parent().shownItem) == $dyn.value($data.Value),
                click: function () { $parent().selectedIndex($index); },
                enabled: $dyn.value($parent().Enabled) && ($dyn.value($parent().AllowEdit) || $dyn.value($parent().shownItem) == $dyn.value($data.Value)),
                attr: {
                    name: $parent().Name,
                },
                valueReadonly: $data.Value" />
            <label class="label radioButton-label staticText" data-dyn-bind="
                text: $data.Label,
                showLabel: { Label: $data.Label, AllowBlankLabel: true },
                superTooltip: $dyn.ui.superTooltip($data),
                attr: {
                    'for': $parent().Id + '_option_' + $index
                }">
            </label>
        </div>
    </div>
</div>

<div id="Image" class="image" data-dyn-focus=".image-binderElement" data-dyn-bind="
    visible: $data.Visible,
    sizing: $data.imageSizing(),
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }">
    <label class="label staticText" data-dyn-bind="
           id: $data.Id + '_label',
           title: $data.Label,
           ariaLabelFor: $dyn.ui.ariaLabelFor($data.Id + '_img', $data),
           showLabel: { Label: $data.Label },
           superTooltip: $dyn.ui.superTooltip($data),
           attr: {'data-dyn-helptext': $data.Tooltip }"></label>
    <span role="img" class="image-binderElement" data-dyn-bind="
        id: $data.Id + '_img',
        img: $dyn.options(function() { return { imageType: $data.ImageType, imageName: $data.ImageName, altText: $data.Tooltip}; }, $data.Updating),
        click:  $data.clicked,
        keyDown: $data.keyDown,
        superTooltip: $dyn.ui.superTooltip($data),
        skip: function() {
                if ($dyn.util.isEnhancedTabSequenceEnabled()) {
                    return { skip: false };
                }

                return $dyn.ui.skip($data);
              }(),
        preview: $dyn.ui.preview($data),
        imgFontSize: $dyn.options(function() { return { imageType: $data.ImageType, height: $data.Height, width: $data.Width, inGrid: $data.isInGrid() }; }, $data.Updating),
        sizing: { height: $data.isInGrid() ? $dyn.layout.Size.content : $data.LayoutHeight,
                  width: $data.isInGrid() ? $dyn.layout.Size.content : $data.LayoutWidth },
        ariaLabelImage: $dyn.ui.ariaLabelImage($data),
        attr: {
            name: $data.Name,
        },">
    </span>
</div>

<div id="ImageCell" class="image" data-dyn-focus=".image-binderElement" data-dyn-bind="
       visible: $data.Visible,
       sizing: $data.imageSizing(),
       preview: $dyn.ui.preview($data),
       layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }">
    <label class="label staticText" data-dyn-bind="id: $data.Id + '_label', ariaLabelFor: $dyn.ui.ariaLabelFor($data.Id, $data), title: $data.Label"></label>
    <span class="image-binderElement" tabindex="-1" data-dyn-bind="
          onClick: $data.queueClickCell,
          img: $dyn.options(function() { return { imageType: $data.ImageType, imageName: $data.ImageName, altText: $data.Tooltip}; }, $data.Updating),
          imgFontSize: $dyn.options(function() { return { imageType: $data.ImageType, height: $data.Height, width: $data.Width, inGrid: $data.isInGrid() }; }, $data.Updating),
          sizing: { height: $data.isInGrid() ? $dyn.layout.Size.content : $data.LayoutHeight,
                    width: $data.isInGrid() ? $dyn.layout.Size.content  : $data.LayoutWidth }">
    </span>
</div>

<span id="Label" class="staticText layout-ignoreArrange" data-dyn-bind="
    text: { text: $dyn.value($data.Text), emptyStr: '&nbsp;' /* Use non-breaking space to maintain height when using an empty string. */},
    sizing: $dyn.layout.sizing($data),
    extendedStyle: $data.Style,
    foregroundColor: $data.ForegroundColor,
    backgroundColor: $data.BackgroundColor,
    title: $dyn.value($data.HelpText),
    superTooltip: $dyn.ui.superTooltip($data),
    ariaLevel: true,
    visible: $data.Visible,
    skip: function() {
        if ($dyn.value($data.Text) == '') {
            return { skip: true };
        }
        if ($dyn.util.isEnhancedTabSequenceEnabled()) {
            return { skip: false };
        }

        return  { skip: true }; /* static text forced to true on client */
        }(),
    ">
</span>

<span id="FieldHelpSection" class="field-help"
    data-dyn-bind="
        id: $data.Id + '_helptext',
        text: $dyn.value($parent().LookupButton) ? $dyn.label('Input_LookupGuideHelpText') + ' ' + $dyn.value($data.HelpText) : $dyn.value($data.HelpText)"
    style="display: none; visibility: hidden;">
</span>

<div id="PresenceIndicator" class="skype-presenceIndicator">
    <span class="skype-presenceBox"></span>
</div>

<div id="SimpleReadOnly" data-dyn-bind="
    visible: $data.Visible,
    sizing: $dyn.layout.sizing($data),
    foregroundColor: $data.ForegroundColor,
    backgroundColor: $data.BackgroundColor,
    css: { 'field-empty': $dyn.value($data.isValueEmpty) }">
    <label class="label staticText boundary-focus-skip" data-dyn-bind="
           id: $data.Id + '_label',
           superTooltip: $dyn.ui.superTooltip($data),
           text: $data.Label,
           showLabel: { Label: $data.Label, ShowLabel: $data.ShowLabel }">
    </label>
    <span class="staticText" data-dyn-bind="
        id: $data.Id + '_text',
        text: { text: $dyn.value($data.Text), emptyStr: '&nbsp;' },
        superTooltip: $dyn.ui.superTooltip($data),
        title: $dyn.value($data.toolTip),
        skip: { skip: !$dyn.util.isEnhancedTabSequenceEnabled() }">
    </span>
</div>

<div id="SearchBox" data-dyn-focus=".field"
     data-dyn-bind="keyDown: $data.keyDown,
                    keyUp: $data.keyUp,
                    focusIn: $data.focusin,
                    focusOut: $data.focusout,
                    visible: $data.ShowOnNavBar,
                    css: { 'searchField-focused' : $data.HasFocus },
                    attr: {'data-dyn-placeholder': $dyn.label('GlobalSearchPlaceholder_Navigation')}">
    <div data-dyn-role="Input" class="searchBox-field"
         data-dyn-bind="TextChanged: $data.TextChanged,
                        showToolTip: false,
                        ShowLabel: false,
                        Label: $dyn.label('GlobalSearchPlaceholder_Navigation'),
                        Name: $data.Name + '_searchBoxInput'">
    </div>
    <span class="searchBox-icon" aria-hidden="true" data-dyn-bind="
          mouseUp: $data.focusInput,
          title: $dyn.label('GlobalSearch_NavigationTooltip'),
          superTooltip: $dyn.ui.superTooltip($data),
          attr: {'data-dyn-helptext': $dyn.label('GlobalSearch_NavigationHelpText')},
          "></span>
    <div style="display: none"
         data-dyn-bind="flyout: {
                            target: $($element).parent().find('.searchBox-field'),
                            of: $($element).parent().find('input').first(),
                            flyout: $($element).children('.sysPopup'),
                            show: $data.ShowResultPicker,
                            takeFocus: false,
                            clickSubscriber: $data.flyoutClickSubscriber,
                            positionResize: true,
                            openOnClick: false,
                            skipAria: true
                        }">
        <div role="presentation" class="sysPopup searchBox-flyout flyoutButton-flyOut layout-root-scope">
            <div role="status" class="No-Results-Indicator" data-dyn-bind="visible: $dyn.computed(function() {return $dyn.length($data.ResultList) == 0;}), sizing: { width: $dyn.layout.Size.available }">
                <span data-dyn-bind="text: $dyn.label('Search_NoResultsMessage'), title: $dyn.label('Search_NoResultsMessage')"></span>
            </div>
             <ul role='listbox' class="searchBox-results"
			    data-dyn-bind="id: $data.Id + '_listbox', ariaLabelledBy: { byElementId: $data.Id + '_searchBoxInput_label'},
                    vars: { '$instantSearch': $data }, foreach: {collection:  $data.ResultList},
                    visible: $dyn.computed(function() {return $dyn.length($data.ResultList) > 0;}),">
                <li class="searchBox-listItem button flyout-menuItem" role="option" tabindex="0"
                    data-dyn-bind="
                        id: $instantSearch.Id + '_listbox_item' + $index,
                        attr: {
                            'aria-posinset': $index + 1,
                            'aria-setsize': $length,
                            'aria-selected': $index == $dyn.value($instantSearch.selectedIndex)
                        },
                        click: function () {  $instantSearch.NavigateToResult($data); },">
                    <span class='searchBox-resultName' data-dyn-bind="text: $data.Name, title: $data.Name"></span>
                    <br />
                    <span class='searchBox-resultPath' data-dyn-bind="text: $data.Path, title: $data.Path"></span>
                </li>
             </ul>
        </div>
    </div>
</div>

<div id="CombinedSearch" class="combinedSearch" data-dyn-bind="css: { 'searchField-focused' : $data.HasFocus }, vars: { '$parentData': $data }, focusIn: $data.FocusIn, focusOut: $data.FocusOut, visible: $dyn.value($data.CombinedSearchEnabled)">
    <div class="combinedSearch-field combinedSearch-navigation" data-dyn-controlname="CombinedNavigationSearch" data-dyn-role="CombinedNavigationSearch" data-dyn-bind="
         Visible: $dyn.computed(function() {return $dyn.value($parentData.SelectedSearchType) == 1;})"></div>
    <div class="combinedSearch-field combinedSearch-actions" data-dyn-controlname="CombinedActionSearch" data-dyn-role="CombinedActionSearch" data-dyn-bind="
         Visible: $dyn.computed(function() {return $dyn.value($parentData.SelectedSearchType) == 2;})"></div>
    <div class="combinedSearch-selector" data-dyn-role="ComboBox" data-dyn-bind="
         Items: $data.SearchOptions, Width: $dyn.layout.Size.xsmall, SelectedItem: $data.SelectedSearchType, Name: 'CombinedSearchFieldSelector'"></div>
</div>

<div id="CombinedSearchField" data-dyn-focus=".field" data-dyn-bind="
     keyDown: $data.keyDown,
     keyUp: $data.keyUp,
     focusOut: $data.focusOut,
     visible: $data.Visible,
     attr: { 'data-dyn-placeholder': $data.Placeholder() }
    ">
    <div class="combinedSearch-searchField" data-dyn-role="Input" data-dyn-bind="
        TextChanged: $data.TextChanged,
        showToolTip: false,
        Width: $dyn.layout.Size.medium,
        SearchField: $data,
        CanAcquireFocus: false
        ">
    </div>
    <div style="display: none" data-dyn-bind="
           flyout: {
                target: $($element).parent(),
                flyout: $($element).children('.sysPopup'),
                show: $data.ShowResultPicker,
                positionResize: true,
                openOnClick: false,
           }">
        <div role="presentation" class="sysPopup flyoutButton-flyOut combinedSearch-flyout layout-root-scope">
            <div role="status" class="No-Results-Indicator" data-dyn-bind="visible: $dyn.computed(function() {return $dyn.length($data.ResultList) == 0;}), sizing: { width: $dyn.layout.Size.available }">
                <span data-dyn-bind="text: $dyn.label('Search_NoResultsMessage'), title: $dyn.label('Search_NoResultsMessage')"></span>
            </div>
             <ul role='listbox' class="searchBox-results searchResultsFlyout"
			    data-dyn-bind="id: $data.Id + '_listbox', ariaLabelledBy: { byElementId: $data.Id + '_Input_label'},
                    vars: { '$combinedSearch': $data }, foreach: {collection:  $data.ResultList},
                    visible: $dyn.computed(function() {return $dyn.length($data.ResultList) > 0;}),">
                <li class="searchBox-listItem flyout-menuItem" role="option" data-dyn-bind="
                    id: $combinedSearch.Id + '_listbox_item' + $index,
                    attr: {
                        'aria-posinset': $index + 1,
                        'aria-setsize': $length,
                        'aria-selected': $index == $dyn.value($combinedSearch.SelectedIndex)
                    },
                    click: {callBack: function () { $combinedSearch.clickItem($index); }, stopPropagation: true, stopRightClickPropagation: true }">
                    <span class='searchBox-resultName' data-dyn-bind="text: $data.Label, title: $data.Label"></span> "
                    <span class='searchBox-resultPath' data-dyn-bind="text: $data.Path, title: $data.Path"></span>"
                </li>
             </ul>
        </div>
    </div>
</div>
<div id="MessageBar" data-dyn-controlname="MessageBar" class="messageBar"
      data-dyn-bind="
        sizing: { width: $dyn.layout.Size.available},
        visible: $data.IsVisible">

    <div role="presentation" data-dyn-role="MessageBarSection" class="messageBarSection-Info" data-dyn-bind="
        Expanded: $data.InfoExpanded,
        IsVisible: $data.IsInfoVisible,
        Messages: $data.infoMessages,
        Toggle: $data.InfoToggle,
        CountText: $data.InfoCountText,
        IsToggleVisible: $data.IsInfoToggleVisible,
        IsCloseVisible: $data.IsInfoCloseVisible,
        MessageType: $dyn.messaging.MessageType.information,
        ClearMessages: $data.ClearInfoMessages,
        CanAcquireFocus: false">
    </div>

    <div role="presentation" data-dyn-role="MessageBarSection" class="messageBarSection-Warning" data-dyn-bind="
        Expanded: $data.WarningExpanded,
        IsVisible: $data.IsWarningVisible,
        Messages: $data.warningMessages,
        Toggle: $data.WarningToggle,
        CountText: $data.WarningCountText,
        IsToggleVisible: $data.IsWarningToggleVisible,
        IsCloseVisible: $data.IsWarningCloseVisible,
        MessageType: $dyn.messaging.MessageType.warning,
        ClearMessages: $data.ClearWarningMessages,
        CanAcquireFocus: false">
    </div>

    <div role="presentation" data-dyn-role="MessageBarSection" class="messageBarSection-Error" data-dyn-bind="
        Expanded: $data.ErrorExpanded,
        IsVisible: $data.IsErrorVisible,
        Messages: $data.errorMessages,
        Toggle: $data.ErrorToggle,
        CountText: $data.ErrorCountText,
        IsToggleVisible: $data.IsErrorToggleVisible,
        IsCloseVisible: $data.IsErrorCloseVisible,
        MessageType: $dyn.messaging.MessageType.error,
        ClearMessages: $data.ClearErrorMessages,
        CanAcquireFocus: false">
    </div>
</div>

<div role="presentation" id="MessageBarSection" class="messageBar" 
     data-dyn-bind="
         sizing: { width: $dyn.layout.Size.available },
         css: { 'expanded': $data.Expanded() },
         visible: $data.IsVisible">
    <div role="presentation" class="messageBar-collapseMessageRegion">
        <button data-dyn-controlname="MessageBarToggle" class="messageBar-button messageBar-collapseButton" aria_label="messages found" role="button" type="button"
                data-dyn-bind="
                    visible: $data.IsToggleVisible,
                    click: $data.Toggle,
                    text: $data.CountText,
                    ariaExpanded: $data.Expanded,
                    title: $dyn.value($data.CountText) + ' ' + $label('MessageBox_MessageList'),
                    superTooltip: $dyn.ui.superTooltip($data),
                    attr: {'aria-label': $dyn.value($data.CountText) + ' ' + $label('MessageBox_MessageList') },
                    keyDown: function (event) { if ($dyn.util.isShortcutKeyPressed(event, { keyCode: $dyn.ui.KeyCodes.enter })) { $data.Toggle(); } }"></button>
        <button data-dyn-controlname="MessageBarClose" class="messageBar-button messageBar-closeIcon Cancel-symbol" role="button" type="button"
                data-dyn-bind="
                    visible: $data.IsCloseVisible,
                    title: $label('Shell_HideNotificationPopup'),
                    superTooltip: $dyn.ui.superTooltip($data),
                    attr: {'aria-label': $label('MessageBox_Close')},
                    click: $data.ClearSectionMessages,
                    keyDown: function (event) { if ($dyn.util.isShortcutKeyPressed(event, { keyCode: $dyn.ui.KeyCodes.enter })) { $data.ClearSectionMessages(); } }"></button>
    </div>
    <div role="presentation" class="messageBar-messageRegion">
        <ol class="messageBar-holder" 
             data-dyn-bind="foreach: { collection: $data.Messages, postRender: $data.PostRenderSection, preRender: $data.PreRenderSection },
             attr: {'aria-label': $dyn.value($data.CountText) + ' total messages ' + $dyn.messaging.getMessageBarAriaLabel($data.MessageType) },
             css: { 'messageBar-message-truncate': $dyn.value($data.IsVisible) && !$data.Expanded() }">
            <li class="messageBar-messageEntry messageBar-slideInT fadeIn">
                <span role="presentation" class="messageBarSection-Icon"></span>
                <span class="messageBar-message" data-dyn-bind="id: $data.messageId + '_text', text: $data.text, title: $data.text, superTooltip: $dyn.ui.superTooltip($data),
                             css: { 'messageBar-message-hasClickLink': $data.ShowExtraMessageText }"></span>
                <span role="button" class="messageBar-message messageBar-detailLink" tabindex="0" data-dyn-bind="text: $data.ActionMessageText, link: $dyn.ui.link($data), visible: $data.ShowActionMessageLink, keyDown: $data.keyDown, title: $data.ActionMessageText, superTooltip: $dyn.ui.superTooltip($data)"></span>
                <span class="messageBar-message messageBar-detailLink" data-dyn-bind="text: $data.messageText, visible: $data.ShowExtraMessageText, title: $data.messageText, superTooltip: $dyn.ui.superTooltip($data)"></span>
            </li>
        </ol>
    </div>
</div>

<div id="PrefixMessageSection" class="prefixMessageSection" data-dyn-bind="
        sizing: { width: $dyn.layout.Size.available},
        visible: true,
        Caption: $label('Shell_PrefixMessagePane_Title')">
    <div class="prefixMessage-heading" data-dyn-bind="text: $data.prefixSection.sectionTitle"></div>

    <div data-dyn-role="PrefixMessageItem" data-dyn-bind="PrefixItems: $data.prefixSection.prefixItemList"></div>

    <div class="prefixMessage-footer" data-dyn-bind="text: $label('Shell_PrefixMessagePane_MaxMessages'), visible: $data.maxMessageCount"></div>
    <div class="prefixMessage-footer" data-dyn-bind="text: $label('Shell_PrefixMessagePane_MaxMessagesPlease'), visible: $data.maxMessageCount"></div>
</div>

<div id="PrefixMessageItem" class="prefixMessageItem" data-dyn-bind="foreach: $data.PrefixItems">
    <div>
        <div role="presentation" data-dyn-bind="if: $dyn.computed(function () { return $data.prefixItemType == 2; })">
            <div class="prefixMessage-messageEntry">
                <div class="prefixMessage-statusIcon" data-dyn-bind="
                        attr: {'data-dynamics-ax-messageicontype': $data.getMessageIconType()}"></div>
                <div tabindex="0" role="textbox" class="prefixMessage-messageText" data-dyn-bind="
                        text: $data.text,
                        attr: {'aria-label': $data.getMessageIconType()}"></div>
                <div tabindex="0" role="button" class="prefixMessage-messageText messageBar-detailLink" data-dyn-bind="
                        text: $data.ActionMessageText,
                        link: $dyn.ui.link($data),
                        visible: $data.ShowStaticActionMessageLink,
                        keyDown: $data.keyDown,
                        title: $data.ActionMessageText,
                        superTooltip: $dyn.ui.superTooltip($data)"></div>
            </div>
        </div>

        <div class="prefixMessage-section" role="presentation" 
            data-dyn-bind="if: $dyn.computed(function () { return $data.prefixItemType == 1; })">
            <button class="messageBar-button prefixMessageBar-collapseButton" tabindex="0" data-dyn-bind="
                id: 'PrefixMessageSectionToggle_' + $data.id,
                click: function() { $data.sectionExpanded(!$data.sectionExpanded()) },
                keyDown: $data.keyDown,
                label: $data.sectionTitle,
                text: { text: $dyn.value($data.sectionTitle), emptyStr: '&nbsp;' /* Use non-breaking space to maintain height when using an empty string. */},
                superTooltip: $dyn.ui.superTooltip($data),
                ariaExpanded: $data.sectionExpanded(),
                attr: { 'aria-controls': 'PrefixMessageSectionToggle_' + $data.id + '_container'}">
            </button>

            <div data-dyn-bind="id: 'PrefixMessageSectionToggle_' + $data.id + '_container', visible: $data.sectionExpanded">
                <div data-dyn-role="PrefixMessageItem" data-dyn-bind="PrefixItems: $data.prefixItemList"></div>
            </div>
        </div>
    </div>
</div>

<div id="CompanyButton" data-dyn-controlname="companybutton" 
    data-dyn-bind="
        helpText: $dyn.label('NavBar_CompanyPickerHelpText'),
        attr: {'data-dyn-expanded': $dyn.value($data.CompanyLookupVisible)}">
    <div class="navigationBar-companyLookup layout-root-scope" data-dyn-bind=
        "visible: $data.CompanyLookupVisible,
        attr: {
            'aria-label': $dyn.label('NavBar_Lookup'),
        }
    ">
        <div id="navigationbar_companychooser"
             data-dyn-controlname="NavigationBar_CompanyChooser"
             data-dyn-role="CompanyChooser"
             class="navigationBar-companyPart"
             data-dyn-bind="
                Width: $dyn.layout.Size.fixed,
                Height: $dyn.layout.Size.fixed,
                ObjectName: 'SysCompanyChooser',
                InitPartForm: $dyn.serverForm.serializers.InitPartForm.deserialize(),
                CreatePartForm: $dyn.serverForm.serializers.CreatePartForm.deserialize(),
             ">
        </div>
    </div>

    <button id="CompanyButton"
            class="navigationBar-companyButton"
            data-dyn-controlname="UserCompany"
            type="button"
            data-dyn-bind="
                title: $dyn.value($data.CompanyName) + ' (' + $dyn.value($data.Company) + ')',
                visible: $data.CompanyName,
                text:  $data.Company,
                click: $data.click,
                keyDown: $data.keyDown,
                visible: $data.ShowOnNavBar,
                superTooltip: $dyn.ui.superTooltip($data),
                attr: {
                    'name': $data.Name,
                    'aria-label': $data.getCurrentCompanyText()
                }
                "></button>
</div>

<div id="PopoutCompanyButton" role="presentation" data-dyn-controlname="popoutcompanybutton">
    <span id="PopoutCompany"
            class="navigationBar-companyButton"
            data-dyn-controlname="PopoutUserCompany"
            data-dyn-bind="
                title: $dyn.value($data.CompanyName) + ' (' + $dyn.value($data.Company) + ')',
                text:  $data.Company,
                superTooltip: $dyn.ui.superTooltip($data),
            ">
    </span>
</div>

<div id="UserButton" data-dyn-controlname="UserButton">
    <button id="UserBtn"
            type="button"
            class="navigationBar-button" data-dyn-bind="
            superTooltip: $dyn.ui.superTooltip($data),
            title: $data.UserName,
            focusIn: $data.focusIn,
            skip: $dyn.ui.skip($data),
            visible: $data.ShowOnNavBar,
            keyDown: $data.keyDown,
            flyout: { flyout: $('.navigationBar-userFlyOut'), show: $data.UserFlyoutVisible },
            attr: {
                'data-dyn-helptext': $data.Alias,
                'name': $data.UserName
            }
            ">
        <img  class="navigation-bar-userAvatar" data-dyn-bind="attr: { 'src' : $data.UserAvatar }, visible: $data.UseAvatarImage" />
        <span class="navigation-bar-userInitials" data-dyn-bind="text: $data.UserInitials, visible: $data.UseAvatarInitials"></span>  
    </button>
    <div class="sysPopup navigationBar-userFlyOut flyoutButton-flyOut layout-root-scope" style="display: none;">
        <ul class="navigationBar-userFlyOutContent">
            <li class="navigationBar-userFlyoutUserName">
                <span data-dyn-bind="text: $data.UserName, title: $data.UserName"></span>
                <br />
                <span data-dyn-bind="text: $data.Alias, title: $data.Alias"></span>
            </li>
            <li>
                <a data-dyn-role="AnchorButton" data-dyn-controlname="SignOut" buttonstyle="Link" data-dyn-bind="Label: $label('User_SignOut'), Click: $dyn.shell.logOut"></a>
            </li>
        </ul>
    </div>
</div>

<div id="PopoutUserButton" data-dyn-controlname="PopoutUserButton">
    <span id="PopoutUser" class="navigationBar-button" data-dyn-bind="visible: false"></span>
</div>

<div id="Default" data-dyn-bind="
    text: $dyn.format($dyn.label('DefaultControl_Text'), $data.TypeName,
                      function (type) {
                          if (type == 'HTML' || type == 'ActiveX' || type == 'ManagedHost' || type == 'Animate') {
                              return $dyn.format($dyn.label('DefaultControl_UnsupportedControlMessage'), type);
                          } else {
                              return '';
                          }
                      }($data.TypeName))"></div>

<div id="Hidden" style="display: none;" data-dyn-bind=""></div>

<div id="NavigationSearchButton" class="navigationBar-search"
     data-dyn-bind="visible: !$dyn.value($data.CombinedSearchEnabled), attr: {'data-dyn-expanded': $dyn.value($data.SearchFieldVisible)}">
    <div class="navigationBar-searchField" role="search" data-dyn-bind="visible: $data.SearchFieldVisible">
        <div class="navigationBar-symbolButton" data-dyn-role="SearchBox" data-dyn-controlname="NavigationSearchBox" id="NavigationSearchBox">
        </div>
    </div>
    <button id="NavigationSearchExpandableControl" data-dyn-role="Button"
            class="navigationBar-button navigationBar-searchButtonCollapsed" 
            data-dyn-bind="
                Visible: $data.SearchFieldNotVisible,
                focusIn: $data.focusIn,
                Label: $dyn.label('GlobalSearch_NavigationTooltip'),
                HelpText: $dyn.label('GlobalSearch_NavigationHelpText'),
                ImageType:'Symbol',
                ButtonDisplay: 'ImageOnly',
                ImageName:'Find',
                Click: $data.click,
                superTooltip: $dyn.ui.superTooltip($data),"></button>
</div>
<div id="Tree" class="treeView" tabindex="-1" data-dyn-bind="
    visible: $data.Visible,
    enabled: $data.Enabled,
    sizing: $dyn.layout.sizing($data),
    treeCheckBox: $data.CheckBox,
    keyDown: $data.keyDown,
    focusIn: $data.focusInCallBack,
    focusOut: $data.focusOutCallBack,
    mouseDown: $data.mouseDown">
</div>

<div id="ProgressBar" class="progressBar" role="progressbar" aria-atomic="true" aria-relevant="all" tabindex="0"
    data-dyn-bind="
    visible: $data.Visible, 
    enabled: $data.Enabled, 
    isIndeterminate: $data.IsIndeterminate,
    sizing: $dyn.layout.sizing($data),
    attr: {
        'aria-valuemin': $data.MinimumValue, 
        'aria-valuemax': $data.MaximumValue,
        'aria-valuenow': $data.Value,
    }">
    <div class="progressBar-indicator-container">
        <div class="progressBar-indicator" data-dyn-bind="width: { value: $value($data.Percent), unit: '%'}"></div>
    </div>
    <div class="activity">
        <div class="activity-item"></div>
        <div class="activity-item"></div>
        <div class="activity-item"></div>
        <div class="activity-item"></div>
        <div class="activity-item"></div>
    </div>
</div>

<div id="StateMachineStage" data-dyn-bind="visible: $data.Visible">
    <span class="stateMachineStage-stateMachineName" data-dyn-bind="text: $data.StateMachineName"></span>
    <div id="stateMachineStage-stages-div">
        <ol id="stateMachineStage-stages" class="stateMachineStage-stages" data-dyn-bind="foreach: $data.Stages">
            <li class="stateMachineStage-stage" data-dyn-bind="attr: { 'data-stage-status': $data.StageStatus }, click: function () { $parent().Select($index); }">
                <span class="stateMachineStage-stageNumber" data-dyn-bind="text: $index, label: $data.State"></span>
                <span class="stateMachineStage-stageDescription" data-dyn-bind="selected: $parent().IsSelected($index), text: $data.State"></span>
            </li>
        </ol>
    </div>
    <div class="stateMachineStage-stageState">
        <span class="stateMachineStage-state" data-dyn-bind="text: $data.StageText()"></span>
    </div>
</div>
<div id="DocumentViewer" class="documentViewer" role="document" data-dyn-bind="
    mouseLeave: $data.CloseDocumentsViewerFlyout,
    sizing: $dyn.layout.sizing($data),
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
    css: {
        'fixed-width': true,
        'fixed-height': true,
    }">
    <div class="documentViewerToolBar" data-dyn-role="Toolbar" data-dyn-bind="
        Visible: $data.ToolBarShown,
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.content }">
        <div data-dyn-role="ToolbarGroup">
            <button data-dyn-role="Button" data-dyn-bind="
                Name: $data.Name + 'ToolbarAddButton',
                Label: $dyn.label('DocumentViewer_AddButtonLabel'),
                ImageName: 'Add',
                ImageType: 'Symbol',
                ButtonDisplay: '',
                Click: $data.AddNewDocument,
                mouseEnter: $data.CloseDocumentsViewerFlyout,
                Visible: $data.AllowUpload"></button>
            <div data-dyn-role="MenuButton" data-dyn-bind="
                Name: $data.Name + 'ToolBarMenuButton',
                ImageName: 'Action',
                ImageType: 'Symbol',
                ButtonDisplay: ''">
                <button data-dyn-role="MenuItem" data-dyn-bind="
                    Name: $data.Name + 'ToolBarOpenMenuItem',
                    Label: $dyn.label('DocumentViewer_OpenButtonLabel'),
                    Click: $data.DownloadDocumentClicked,
                    mouseEnter: $data.CloseDocumentsViewerFlyout"></button>
                <button data-dyn-role="MenuItem" data-dyn-bind="
                    Name: $data.Name + 'ToolBarDeleteMenuItem',
                    Label: $dyn.label('DocumentViewer_DeleteButtonLabel'),
                    Click: $data.DeleteDocumentClicked,
                    mouseEnter: $data.CloseDocumentsViewerFlyout,
                    Visible: $data.AllowDelete"></button>
            </div>
            <button data-dyn-role="Button" data-dyn-bind="
                Name: $data.Name + 'DocumentViewerDocumentsPreview',
                Label: $dyn.label('DocumentViewer_AttachmentsButtonLabel'),
                ImageName: 'DropDownArrow',
                ImageType: 'Symbol',
                ButtonDisplay: $dyn.ui.ButtonDisplay.textWithImageRight,
                Click: $data.AttachmentsButtonClicked,
                mouseEnter: $data.CloseDocumentsViewerFlyout,
                Visible: $data.AttachmentsButtonShown"></button>
        </div>
    </div>
    <div class="documentViewerEmpty" data-dyn-bind="
        visible: $data.ViewerEmpty,
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available }">
        <div>
            <button data-dyn-role="Button" data-dyn-bind="
                Name: $data.Name + 'ToolbarEmptyAddButton',
                Label: $dyn.label('DocumentViewer_EmptyAddButtonLabel'),
                ImageName: 'Add',
                ImageType: 'Symbol',
                ButtonDisplay: '',
                Click: $data.AddNewDocument,
                Visible: $data.EmptyViewerAddButtonVisible"></button>
            <span data-dyn-role="Label" data-dyn-bind="
                Name: $data.Name + 'EmptyViewerLabel',
                Text: $data.EmptyViewerLabel,
                Visible: $data.EmptyViewerLabelVisible"></span>
        </div>
    </div>
    <div class="documentViewerPreview" data-dyn-bind="
        visible: $data.HasDocumentPreview,
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available, ignoreSiblings: true }">
        <iframe src="" sandbox="" data-dyn-bind="Title: $dyn.label('DocumentViewer_IframeTitle')"></iframe><!-- lgtm[js/insufficient-iframe-sandboxing] -->
    </div>
    <div class="documentViewerNoPreview" data-dyn-bind="
        visible: $data.HasDocumentNoPreview,
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available, ignoreSiblings: true }">
        <div class="documentViewerNoPreviewContainer">
            <h1 data-dyn-role="Label" data-dyn-bind="Text: $dyn.label('DocumentViewer_NoPreviewText')"></h1>
            <p data-dyn-role="Label" data-dyn-bind="Text: $dyn.label('DocumentViewer_NoPreviewExpandedText')"></p>
            <div>
                <img data-dyn-bind="
                    attr: { 'src' : $data.PreviewSrcThumbnail }" />
            </div>
            <div>
                <span data-dyn-role="Label" class="documentViewerAttribute" data-dyn-bind="
                    Name: $data.Name + 'NoPreviewFileNameLabel',
                    Text: $dyn.label('DocumentViewer_NoPreviewFileNameLabel')"></span>
                <span data-dyn-role="Label" data-dyn-bind="
                    Name: $data.Name + 'NoPreviewFileNameValueLabel',
                    Text: $data.PreviewDocumentName"></span>
                <span data-dyn-role="Label" class="documentViewerAttribute" data-dyn-bind="
                    Name: $data.Name + 'NoPreviewDateLabel',
                    Text: $dyn.label('DocumentViewer_NoPreviewDateLabel')"></span>
                <span data-dyn-role="Label" data-dyn-bind="
                    Name: $data.Name + 'NoPreviewDateValueLabel',
                    Text: $data.PreviewDate"></span>
            </div>
        </div>
    </div>
    <div class="documentViewerFlyOutDiv" style="display:none" data-dyn-bind="
        mouseLeave: $data.CloseDocumentsViewerFlyout">
        <ul data-dyn-bind="foreach: $data.Documents" data-dyn-template-applied="true">
            <li data-dyn-bind="
                click: $parent().DocumentViewerFlyoutOptionClicked,
                css: { 'documentViewerSelectedDocument' : $data.Selected == 1},
                attr: { 'docu-value-rec-id' : $data.DocuValueRecId }">
                <div>
                    <img data-dyn-bind="
                        attr: { 'src': $data.ThumbnailImageUrl }" />
                    <span data-dyn-role="Label" data-dyn-bind="
                        Text: $data.Name"></span>
                    <span data-dyn-role="Label" data-dyn-bind="
                        Text: $data.FriendlyLastModified"></span>
                </div>
            </li>
        </ul>
    </div>
</div>

<div id="DocumentUpload" aria-live="assertive" aria-atomic="true" aria-relevant="all" data-dyn-focus=".button" data-dyn-bind="visible: $data.Visible, enabled: $data.Enabled,
    label: $dyn.label('DocumentUpload_FileUploadCaption'),
    css: { 'docuUploadMinimal' : $dyn.value($data.Style) == $dyn.ui.DocuUploadStyle.MinimalStyle }">
    <div data-dyn-bind="layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }">
        <div data-dyn-role="Input" class="docuUpload-FileName" data-dyn-bind="
            Name: $data.Name + 'SelectedFileInput',
            AllowEdit: false,
            Value: $data.selectedFile,
            Label: $dyn.label('DocumentUpload_FileUploadCaption'),
            ShowLabel: $dyn.value($data.Style) != $dyn.ui.DocuUploadStyle.MinimalStyle"></div>
        <div class="docuUpload-fileInputControl">
            <button data-dyn-role="Button" data-dyn-bind="
                Name: $data.Name + 'BrowseButton',
                Label: $dyn.label('DocumentUpload_BrowseButtonLabel'),
                Click: $data.BrowseButtonClicked,
                Enabled: $data.buttonsEnabled"></button>
            <input class="docuUpload-fileInput" type="file" data-dyn-bind="
                id: $data.Id + '_input',
                attr: { 'doc-upload-file-input': $data.Name }" />
        </div>
    </div>
    <div class="docuUpload-docuUploadInputs">
        <div data-dyn-role="Input" data-dyn-bind="
            Name: $data.Name + 'NotesInput',
            AllowEdit: $data.SubControlsAllowEdit,
            Visible: !$dyn.value($data.HideNotes),
            Label: $dyn.label('DocumentUpload_NotesLabel'),
            Value: $data.Notes"></div>
        <div data-dyn-role="Input" data-dyn-bind="
            Name: $data.Name + 'DocuNameInput',
            AllowEdit: $data.SubControlsAllowEdit,
            Visible: !$dyn.value($data.HideDocuName),
            Label: $dyn.label('DocumentUpload_NameLabel'),
            Value: $data.DocuName"></div>
        <div data-dyn-role="ComboBox" data-dyn-bind="
            Name: $data.Name + 'DocuTypesComboBox',
            Label: $dyn.label('DocumentUpload_DocuTypeLabel'),
            SelectedItem: $data.SelectedDocumentType,
            Items: $data.DocumentTypes,
            Enabled: $data.Enabled,
            AllowEdit: $data.SubControlsAllowEdit,
            ShowLabel: true"></div>
    </div>
    <div class="docuUpload-docuUploadButtons">
        <button data-dyn-role="Button" data-dyn-bind="
            Name: $data.Name + 'UploadButton',
            Label: $dyn.label('DocumentUpload_UploadButtonLabel'),
            Click: $data.UploadButtonClicked,
            Enabled: $data.UploadButtonEnabled"></button>
    </div>
</div>

<div id="FileUpload" class="FileUpload" aria-live="polite" data-dyn-focus=".button" data-dyn-bind="visible: $data.Visible, enabled: $data.Enabled, label: $dyn.value($data.FileNameLabel),
    css: { 'minimal' : $dyn.value($data.Style) == $dyn.ui.FileUploadStyle.MinimalStyle, 'minimalWithFilename' : $dyn.value($data.Style) == $dyn.ui.FileUploadStyle.MinimalWithFileNameStyle }">
    <span data-dyn-role="Label" class="fileUpload-Label" data-dyn-bind="
        Name: $data.Name + 'FileNameLabel',
        Text: $dyn.value($data.FileNameLabel)"></span>
    <div class="filePickerContainer" data-dyn-bind="
        Name: $data.Name + 'FileNameInput',
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.content },
        layout: { arrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft }">
        <div data-dyn-role="Input" class="fileUpload-FileName" data-dyn-bind="
            Label: $dyn.label('FileUpload_FileNameInputLabel'),
            Name: $data.Name + 'FileNameDisplay',
            AllowEdit: false,
            Value: $data.fileNameDisplayValue"></div>
        <div role="presentation" class="fileUpload-fileInputControl">
            <button data-dyn-role="Button" data-dyn-bind="
                Name: $data.Name + 'BrowseButton',
                Label: $data.BrowseText,
                Enabled: $data.browseEnabled,
                Click: $data.BrowseButtonClicked"></button>
            <input class="fileUpload-fileInput" type="file" data-dyn-bind="
                id: $data.Id + '_input',
                attr: { 'accept': $data.CommonFileTypesAccepted,
                        'file-upload-file-input': $data.Name }" />
        </div>
    </div>
    <div data-dyn-role="ProgressBar" data-dyn-bind="
        Name: $data.Name + 'FileUploadProgressBar',
        Value: $data.ProgressPercent,
        Visible: $data.DisplayProgressBar"></div>
    <button data-dyn-role="Button" class="fileUpload-Upload" data-dyn-bind="
        Name: $data.Name + 'UploadButton',
        Label: $dyn.label('FileUpload_UploadButtonLabel'),
        Enabled: $data.UploadButtonEnabled,
        Click: $data.SubmitButtonClicked"></button>
    <button data-dyn-role="Button" class="fileUpload-Cancel" data-dyn-bind="
        Name: $data.Name + 'CancelButton',
        Label: $dyn.label('FileUpload_CancelButtonlabel'),
        Enabled: $data.cancelEnabled,
        Click: $data.CancelButtonClicked"></button>
</div>

<div id="ContextMenu" role="menu" class="sysPopup flyoutButton-flyOut contextMenuContainer layout-root-scope" data-dyn-bind="
    vars: { '$parentData': $data },
    foreach: { collection:  $data.List, postRender: $data.postRender },
    mouseEnter: function () { $data.isHovered(true); },
    mouseLeave: function () { $data.isHovered(false); }, ">
    <div data-dyn-bind="visible: true">
        <div data-dyn-bind="if: $data.contextMenuOptions && $data.contextMenuOptions.length > 0 ">
            <button class="contextMenuButton" data-dyn-role="SubMenuButton" data-dyn-bind="
                id: $data.Id + '_subMenuButton',
                accessibilityAttributes: {'index': $data.index, 'length': $data.length}"></button>
        </div>

        <div data-dyn-bind="if: $data.contextMenuOptions === undefined || $data.contextMenuOptions.length == 0 ">
            <button class="contextMenuButton" data-dyn-role="MenuItem" data-dyn-bind="
                Label: $data.Label,
                accessibilityAttributes: {'index': $data.index, 'length': $data.length},
                Click: $data.Command,
                Enabled: $data.Enabled,
                id: $data.Id + '_contextMenuButton', "></button>
        </div>
    </div>
</div>

<button id="SubMenuButton" role="button" class="contextMenuButton button flyout-menuItem" type="button" data-dyn-bind="
    visible: $data.Visible,
    enabled: $data.Enabled,
    click: $data.Clicked,
    keyDown: $data.keyDown,
    extendedStyle: $data.Style,
    skip: $dyn.ui.skip($data),
    attr: { 
        'data-dyn-button-display': $data.buttonDisplay,
        'aria-posinset': $data.accessibilityAttributes && $data.accessibilityAttributes.index + 1,
        'aria-setsize': $data.accessibilityAttributes && $data.accessibilityAttributes.length,
    },
    mouseEnter: function () { $data.isHovered(true); },
    mouseLeave: function () { $data.isHovered(false); }, ">
    <div class="button-container">
        <span class="button-commandRing" data-dyn-bind="img: $dyn.ui.img($data)"></span>
        <span class="button-label" data-dyn-bind="id: $data.Id + '_label', labelFor: $dyn.ui.labelFor($element.parentNode.parentNode, $data, $data.Label)"></span>
    </div>
</button>

<div id="AppBarSection" role="presentation" data-dyn-container="true" class="appBar layout-reflow-scope" data-dyn-bind="
     visible: $data.Visible,
     sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.content },
     css: { 'appBar-isPinned': $data.IsPinnedOpen }">
    <div class="appBar-toolbar" role="toolbar">
        <div class="actionPane-replace" data-dyn-content="replace: '[data-dyn-role=ActionGroup]:not(.actionGroup-right)'" style="display: none;"></div>
        <div class="actionPane-replace" data-dyn-content="replace: '[data-dyn-role=AppBarTab]'" style="display: none;"></div>
        <div data-dyn-role="AppBarSearchField" data-dyn-controlname="AppBarSearch" class="actionSearch"></div>
        <div class="appBar-overflow" data-dyn-role="OverflowButton" data-dyn-bind="Visible: $data.ShowOverflowButton, MenuOpen: $data.OverflowMenuOpen, ClickSubscriber: $data.overflowClickSubscriber"></div>
        <div class="actionPane-replace actionGroup-right" data-dyn-content="replace: '[data-dyn-role=ActionGroup].actionGroup-right'" style="display: none;"></div>
    </div>
</div>

<div id="OverflowButton" class="overflow-button More-symbol " role="button" tabindex="0" data-dyn-bind="
             visible: $data.Visible,
             title: $dyn.label('AppBar_OverflowToolTip'),
             superTooltip: $dyn.ui.superTooltip($data),
             flyout:{
                flyout: $('.overflow-menu', $element),
                show: $data.MenuOpen,
                positionResize: true, clickSubscriber: $data.ClickSubscriber }">
    <div class="overflow-menu sysPopup allowFlyoutClickPropagation" style="display: none" role="list"></div>
</div>

<div id="AppBarTab" class="appBarTab" data-dyn-bind="
    visible: $data.Visible,
    enabled: $data.Enabled"
     data-dyn-container=".appBarTab-content"
     data-dyn-focus=".appBarTab-header">
    <button class="appBarTab-header allowFlyoutClickPropagation" type="button" data-dyn-bind="
        id: $data.Id + '_button',
        keyDown: $data.keyDown,
        enabled: $data.Enabled,
        focusIn: $data.focusIn,
        click: $data._headerClicked,
        superTooltip: $dyn.ui.superTooltip($data),
        flyout: {
            flyout: $('.appBar-flyout', $element.parentElement),
            show: $data.FlyoutExpanded,
            at: 'manual',
            openOnClick: false,
            clickSubscriber: $data.flyoutClickSubscriber,
            entranceAnimation: 'appBar-growHeight',
            exitAnimation: $data.flyoutExitAnimation,
            }">
        <span class="appBarTab-headerLabel allowFlyoutClickPropagation" data-dyn-bind="
              text: $data.Label">
        </span>
    </button>
    <div class="appBar-flyout layout-root-scope allowFlyoutClickPropagation" data-dyn-stop-binding="true" role="toolbar" style="display: none" data-dyn-bind="
         id: $data.Id + '_flyout',
         css: {
         'appBar-asidePaneOpen' : $dyn.shell.isAsidePaneOpen,
         'appBar-isNavigationPanePinned' : $dyn.shell.isNavigationPanePinned,
         'appBar-isPopout': $dyn.popout,
         'appBar-taskRecorderToolbarOpen': $dyn.shell.isTaskRecorderToolbarOpen }">
        <div class="appBarTab-content" data-dyn-content="append: '*'"></div>
        <button class="appBar-pin" type="button" data-dyn-bind="
            id: $data.Id + '_pin',
            title: $data.pinButtonLabel,
            click: $data._togglePinnedState,
            superTooltip: $dyn.ui.superTooltip($data),
            css: {
             'ChevronUp-symbol': $dyn.value($dyn.shell.isSmallViewPort) || $dyn.value($data.IsAppBarPinnedOpen),
             'Pin-symbol': !$dyn.value($dyn.shell.isSmallViewPort) && !$dyn.value($data.IsAppBarPinnedOpen),
            }">
        </button>
    </div>
</div>

<div id="AppBarSearchField" data-dyn-focus=".field" data-dyn-bind="
     keyDown: $data.keyDown,
     keyUp: $data.keyUp,
     focusIn: $data.focusin,
     focusOut: $data.focusout,
     css: { 'actionSearch-hasFieldShown' : $data.SearchFieldShown },
     attr: { 'data-dyn-placeholder': $dyn.label('AppBarSearch_Label') },
    ">
    <div class="actionSearch-field" data-dyn-role="Input" aria-haspopup="true" data-dyn-bind="
        TextChanged: $data.TextChanged,
        showToolTip: false,
        Width: $dyn.layout.Size.large,
        SearchField: $data,
        CanAcquireFocus: false,
        Name: 'AppBarSearchField',
        Label: $dyn.label('AppBarSearch_Label'),
        ShowLabel: false">
    </div>
    <button class="actionSearch-icon Find-symbol allowFlyoutClickPropagation" type="button" tabindex="0" data-dyn-bind="
        click: $data.searchIconClicked,
        title: $dyn.value($data.SearchFieldShown) ? '' : $dyn.label('AppBarSearch_Label'),
        flyout: {
            target: $($element).parent(),
            flyout: $($element).children('.sysPopup'),
            show: $data.ShowResultPicker,
            positionResize: true,
            openOnClick: false,
        },
        superTooltip: $dyn.ui.superTooltip($data),
        attr: { 'aria-label': $dyn.label('AppBarSearch_Label'), 'data-dyn-helptext': $dyn.label('AppBarSearch_HelpText') },">
        <div role="presentation" class="sysPopup actionSearch-flyout flyoutButton-flyOut layout-root-scope">
            <div role="status" class="No-Results-Indicator" data-dyn-bind="visible: $dyn.computed(function() {return $dyn.length($data.ResultList) == 0; }), sizing: { width: $dyn.layout.Size.available }">
                <span data-dyn-bind="text: $dyn.label('List_NoResultsMessage'), title: $dyn.label('List_NoResultsMessage')"></span>
            </div>
             <ul role='listbox' class="actionSearch-results searchResultsFlyout"
			    data-dyn-bind="id: $data.Id + '_listbox', ariaLabelledBy: { byElementId: $data.Id + '_searchBoxInput_label' },
                    vars: { '$appBarSearch': $data }, foreach: { collection:  $data.ResultList },
                    visible: $dyn.computed(function() { return $dyn.length($data.ResultList) > 0; }),">
                <li class="actionSearch-listItem flyout-menuItem" role="option" tabindex="0"
                    data-dyn-bind="
                        id: $appBarSearch.Id + '_listbox_item' + $index,
                        enabled: $data.Enabled,
                        ariaEnabled: $data.Enabled,
                        attr: {
                            'aria-posinset': $index + 1,
                            'aria-setsize': $length,
                            'aria-selected': $index == $dyn.value($appBarSearch.SelectedIndex)
                        },
                        click: { callBack: function () { if($data.Enabled) { $appBarSearch.clickItem($index); } }, stopPropagation: true },">
                    <span class='actionSearch-resultsLabel' data-dyn-bind="text: $data.Label"></span>
                    <br />
                    <span class='actionSearch-resultsPath' data-dyn-bind="text: $data.Path"></span>
                </li>
             </ul>
        </div>
    </button>
</div>

<div id="Toolbar" class="toolbar" role="toolbar" data-dyn-bind="visible: $data.Visible, enabled: $data.Enabled, sizing: $dyn.layout.sizing($data)" data-dyn-container="true">
    <div class="toolbar-replace" data-dyn-content="replace: '*'" style="display: none;"></div>
    <div class="toolbar-overflow" data-dyn-role="OverflowButton" data-dyn-bind="id: $data.Id + '_overflow', MenuOpen: $data.OverflowMenuOpen, ClickSubscriber: $data.overflowClickSubscriber"></div>
</div>

<div id="ToolbarGroup" class="toolbar-group" role="group" data-dyn-bind="
     visible: $data.Visible,
     enabled: $data.Enabled"
     data-dyn-container="true">
    <div class="toolbarGroup-replace" data-dyn-content="replace: '*'" style="display: none;"></div>
    <div class="toolbarGroup-overflow" data-dyn-bind="visible: $data.Visible, id: $data.Id + '_overflow'"></div>
</div>

<div role="presentation" id="ActionGroup" data-dyn-bind="
    visible: $data.Visible,
    enabled: $data.Enabled"
    class="actionGroup appBar-button-group"
    data-dyn-container="true">
    <div role="presentation" class="" data-dyn-content="replace: '*'" style="display: none;"></div>
    <div role="presentation" class="actionGroup-overflow" data-dyn-bind="visible: $data.Visible, id: $data.Id + '_overflow'"></div>
</div>

<div role="group" id="AppBarGroup" data-dyn-bind="
    visible: $data.Visible,
    enabled: $data.Enabled"
     class="group button-group" data-dyn-container=".group_content">
    <div role="presentation" class="group_header">
        <label class="group_title" data-dyn-bind="id: $data.Id + '_title', labelFor: $dyn.ui.labelFor($element.parentNode.parentNode, $data, $data.Label)"></label>
    </div>
    <div role="presentation" class="group_content" data-dyn-content="append: '*'" data-dyn-bind="layout: $dyn.layout.containerBinding($data)">
    </div>
</div>

<div id="MessageCenterButton" class="navigationBar-messageControl navigationBar-pinnedElement">
    <button class="navigationBar-symbolButton navigation-bar-notification-button ViewNotifications-symbol"
            data-dyn-controlname="navBarMessageCenter"
            role="button"
            type="button"
            aria-haspopup="true"
            data-dyn-bind="
                id: $data.Id + '_buttonNotifications',
                focusIn: $data.MessageCenterButtonFocus,
                title: $label('NavBar_ShowNotifications'),
                visible: (!$dyn.isEmbedded) || ($dyn.isEmbedded && !$dyn.value($dyn.messaging.MessageCenterManager.messagesEmpty)),
                attr: {
                    'data-dyn-helptext': $dyn.label('NavBar_ShowNotificationsHelpText'),
                    'aria-label': $dyn.format('{0} {1}', $dyn.label('NavBar_ShowNotifications'), $dyn.label('NavBar_ShowNotificationsHelpText')),
                },
                superTooltip: $dyn.ui.superTooltip($data),
                flyout: { flyout: $('.messageCenter'), at: 'left bottom', my: 'left top', collision: 'fit', within: $('#mainPane'), 
                show: $dyn.messaging.MessageCenterManager.messageCenterVisible}">
        <span role="status" class="messageCenter-counter messageCenter-status"
              data-dyn-bind="
                text: $dyn.value($dyn.messaging.MessageCenterManager.unreadMessageCount),
                attr: {'aria-label': $label('MessageCenterNotificationAria')},
                visible: $dyn.value($dyn.messaging.MessageCenterManager.unreadMessageCount) > 0,
                css: { 'highlightGray7toError' : $dyn.value($dyn.messaging.MessageCenterManager.unreadMessageCountChanged) }"></span>
    </button>
    <audio id="dynNotificationBackgroundAudio" preload="none">
        <source data-dyn-bind="src: $dyn.shell.rootPath + 'Resources/Sounds/Notification-Background.mp3'" type="audio/mpeg" />
    </audio>
    <div id="dynNotificationPopup" class="notificationPopup basic-slideInFadeIn"  
        role="alert" class="hidden" aria-live="assertive" aria-relevant="all" aria-atomic="true" style="display:none;" data-dyn-bind="
            focusIn: $dyn.messaging.MessageCenterManager.ClearTimeout,
            mouseEnter: $dyn.messaging.MessageCenterManager.ClearTimeout,
            mouseLeave: $dyn.messaging.MessageCenterManager.ClearToastVariables,
            visible: $dyn.value($dyn.messaging.MessageCenterManager.unreadMessageCountChanged)">
        <div class="notificationPopup-content basic-slideInFadeInInner">
            <div class="notificationPopup-message" tabindex="-1" data-dyn-bind="
                    text: $dyn.value($dyn.messaging.MessageCenterManager.notificationPopupMessage),
                    click: function () { $dyn.messaging.MessageCenterManager.messageCenterVisible(true); }"></div>
            <div class="notificationPopup-link" tabindex="-1" role="button" data-dyn-bind="
                    text: $data.ActionMessageText,
                    link: $dyn.ui.link($data),
                    visible: $data.ShowStaticActionMessageLink,
                    keyDown: $data.keyDown,
                    title: $data.ActionMessageText,
                    superTooltip: $dyn.ui.superTooltip($data)"></div>
        </div>
        <button id="dynNotificationClose" data-dyn-role="SymbolButton" class="notificationPopup-hide"
                data-dyn-bind="ImageType:'Symbol',
                    ButtonDisplay: 'ImageOnly',
                    ImageName:'Cancel',
                    Label: $label('Shell_HideNotificationPopup'),
                    Click: function () {
                        $dyn.messaging.MessageCenterManager.FocusNavBarMessagesButton();
                        $dyn.messaging.MessageCenterManager.ClearToastVariables();
                    }"></button>
    </div>
    <div class="messageCenter" data-dyn-lastvisible="false" role="dialog" aria-modal="true" data-dyn-bind="attr: {'aria-label': $label('MessageCenter_Header')}">
        <h1 class="messageCenter-header" data-dyn-bind="text: $label('MessageCenter_Header') "></h1>
        <div class="messageCenter-buttonBar">
            <span class="staticText messageCenter-messageCount" data-dyn-bind="text: $dyn.messaging.MessageCenterManager.messageCount"></span>
            <div class="messageCenter-buttonBar-right">
                <a data-dyn-role="AnchorButton" class="messageCenter-seeAllMessagesButton" data-dyn-controlname="SeeAllMessages" buttonstyle="Link"
                   data-dyn-bind="Label: $label('MessageCenter_SeeAllLink'), Click: function () { $navBar && $navBar.NavigateToNotificationsForm && $navBar.NavigateToNotificationsForm(); }, Enabled: $dyn.value($dyn.messaging.MessageCenterManager.seeAllMessagesLinkEnabled)"></a>
            </div>
        </div>
        <div class="messageCenter-emptyTextContainer" data-dyn-bind="visible: $dyn.messaging.MessageCenterManager.messagesEmpty">
            <span class="staticText messageCenter-emptyText" 
                data-dyn-bind="text: $label('MessageCenter_NoMessages'),
                    skip: !$dyn.util.isEnhancedTabSequenceEnabled(),
                    attr: {
                        'aria-label': $label('MessageCenter_NoMessages')
                    }"></span>
        </div>

        <ul class="messageCenter-list" role="list" data-dyn-bind="foreach: $dyn.messaging.MessageCenterManager.messages">
            <li class="messageCenter-item" role="listitem" data-dyn-bind="
                attr: {
                    'aria-posinset': $index + 1,
                    'aria-setsize': $length,
                }">
                <span class="staticText messageCenter-statusIcon" aria-haspopup="true"
                    data-dyn-bind="
                        attr: {
                            'data-dynamicsax-status': $data.statusIcon
                        }">
                </span>
                <div class="messageCenter-itemBody" data-dyn-bind="if: $dyn.value($data.isMessage)">
                    <!-- InfoLog Messages -->
                    <span class="staticText messageCenter-itemTitle"
                        data-dyn-bind="
                            text: $data.text,
                            skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                    <span class="staticText messageCenter-itemAction"
                        tabindex="0"
                        role="button"
                        data-dyn-bind="
                            text: $data.ActionMessageText,
                            link: $dyn.ui.link($data),
                            visible: $data.ShowStaticActionMessageLink,
                            keyDown: $data.keyDown,
                            title: $data.ActionMessageText,
                            superTooltip: $dyn.ui.superTooltip($data),
                            skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                    <span class="staticText messageCenter-createdTimeStamp"
                        data-dyn-bind="
                            text: $data.elapsedTimeSinceArrival,
                            skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                    <span class="staticText messageCenter-itemLink"
                        tabindex="0"
                        data-dyn-bind="
                            text: $data.detailText,
                            link: $dyn.ui.link($data),
                            visible: $data.ShowPrefixLink,
                            keyDown: $data.keyDown"></span>
                    <span class="staticText messageCenter-itemMessage"
                        data-dyn-bind="
                            text: $data.messageText,
                            visible: $data.ShowPrefixMessageText,
                            skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                </div>
                <div class="messageCenter-itemBody" data-dyn-bind="if: $dyn.value($data.isAlert) || $dyn.value($data.isWatchDog)">
                    <!-- User-Defined Alert / WatchDog Messages -->
                    <span class="staticText messageCenter-itemTitle"
                        data-dyn-bind="
                            text: $data.text,
                            skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                    <span class="staticText messageCenter-createdTimeStamp"
                        data-dyn-bind="
                            text: $data.formattedCreatedTimeStamp,
                            skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                    <span class="staticText messageCenter-truncateText messageCenter-itemMessage"
                        tabindex="0"
                        data-dyn-bind="
                            text: $data.message,
                            visible: $dyn.value($data.message),
                            keyDown: $data.keyDown "></span>
                    <div class="messageCenter-extraItems">
                        <span class="staticText messageCenter-itemStatusHeader"
                            data-dyn-bind="
                                text: $dyn.label('MessageCenter_StatusHeader'),
                                visible: $dyn.value($data.stateMessage)"></span>
                        <span class="staticText messageCenter-itemStatus"
                            data-dyn-bind="
                                text: $dyn.value($data.stateMessage),
                                visible: $dyn.value($data.stateMessage),
                                skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                        <div class="messageCenter-itemActions" data-dyn-bind="foreach: $data.notificationActions">
                            <div class="staticText messageCenter-itemAction"
                                tabindex="0"
                                data-dyn-bind="
                                    text: $data.Value,
                                    link: $dyn.ui.link($data)"></div>
                        </div>
                    </div>
                </div>
                <div class="messageCenter-itemButtons">
                    <button class="messageCenter-itemButton messageCenter-clearButton" data-dyn-role="Button"
                        data-dyn-bind="
                            Name: 'messageCenterItemClear' + $index,
                            ButtonDisplay: $dyn.ui.ButtonDisplay.imageOnly,
                            ImageType: 'Symbol',
                            ImageName: 'Cancel',
                            Label: $label('MessageBox_Close'),
                            Click: function() { $dyn.messaging.MessageCenterManager.ClearMessage($data) },"></button>
                    <div class="messageCenter-itemButtonContainer" data-dyn-bind="if: $dyn.value($data.isAlert) || $dyn.value($data.isWatchDog)">
                        <button class="messageCenter-itemButton messageCenter-expandButton ChevronDown-symbol" type="button" data-dyn-bind="
                            Name: 'messageCenterItemExpand' + $index,
                            click: function() { $dyn.messaging.MessageCenterManager.ExpandMessage($element) },"></button>
                    </div>
                </div>
            </li>
        </ul>
        <div class="messageCenter-buttonBar">
            <div class="messageCenter-buttonBar-right">
                <a data-dyn-role="AnchorButton" class="messageCenter-clearButton" data-dyn-controlname="ClearMessages" buttonstyle="Link"
                   data-dyn-bind="Label: $label('MessageCenter_ClearMessages'), Click:$dyn.messaging.MessageCenterManager.ClearAndDismissMessages, Visible: $dyn.messaging.MessageCenterManager.messagesNotEmpty"></a>
            </div>
        </div>
    </div>
</div>
<div id="FilterPane" class="filterPane layout-reflow-scope" role="region" aria-relevant="all" data-dyn-bind="
    keyDown: $data.keyDown,
    visible: $data.Visible,
    sizing: { height: $dyn.layout.Size.available },
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
    attr: {
        'aria-live': $dyn.value($data.Visible) ? 'polite' : 'off'
    }">
    <h2 class="filterPaneTitle" data-dyn-bind="text: $label('FilterPane_Filters')"></h2>
    <div data-dyn-role="FilterDisplay" data-dyn-bind="
        Name: $data.Name + '_FilterDisplay',
        Height: $dyn.layout.Size.available,
        FilterExpression: $data.FilterExpression,
        CapabilityList: $data.CapabilityList,
        visible: $data.Visible,
        Enabled: $data.Enabled,
        ApplyFilters: $data.ApplyFilters,
        ResetFilters: $data.ResetFilters,
        AddAFilterField: $data.AddAFilterField,
        ShowAddFilter: true,
        ShowApply: true,
        ShowClear: true,
        ">
    </div>
</div>

<div id="FilterManager" role="region" data-dyn-bind="
    visible: false ">
</div>

<div id="FilterDisplay" class="filterDisplay" role="region" data-dyn-bind="visible: $data.Visible, sizing: $dyn.layout.sizing($data)">
    <!-- Add a filter field using the field selector through the filter pane control -->
    <div class="filterDisplay-addFieldButton" data-dyn-bind="visible: $data.ShowAddFilter, enabled: $data.IsValid">
        <button data-dyn-role="Button" class="filterDisplay-addFieldControl" data-dyn-bind="
            Name: $dyn.value($data.Name) + '_AddFilterField',
            ImageType: 'Symbol',
            ImageName: 'Add',
            ButtonDisplay: $dyn.ui.ButtonDisplay.textWithImageLeft,
            Click: $data.addFilterField,
            HelpText: $label('FilterDisplayControl_AddField'),
            Label: $label('FilterField_AddField')">
        </button>
    </div>
    <div class="filterDisplayContent">
        <!-- Add a filter field for each FieldExpression -->
        <div data-dyn-bind="vars: { '$filterDisplay': $data }, foreach: {collection: $data.FieldExpressions, postRender: $data.postRenderFields}">
            <div data-dyn-role="FilterField" data-dyn-bind="
                    AllowEdit: $dyn.util.stringToBoolean($dyn.value($data.IsEditable)),
                    Operator: $data.Operator,
                    Values: $data.Values,
                    FieldCapability: $filterDisplay.getFieldCapability($dyn.value($data.DataSourceName), $dyn.value($data.FieldName), $dyn.value($data.SFKReplacementFieldBinding)),
                    Name: $dyn.value($filterDisplay.Name) + '_' + $dyn.value($data.DataSourceName) + '_' + $dyn.value($data.FieldName) + $index,
                    RecordingReferences: $data.RecordingReferences
                    ">
            </div>
        </div>
    </div>
    <div class="filterDisplayButtonContainer">
        <div class="filterActions">
            <button data-dyn-role="Button" class="button dynamicsButton" data-dyn-bind="Visible: $data.ShowApply, Click: $data.applyFilters, Label: $label('FilterDisplayControl_Apply'), Name: $dyn.value($data.Name) + '_ApplyFilters'"></button>
            <button data-dyn-role="Button" class="button dynamicsButton" data-dyn-bind="Visible: $data.ShowClear, Click: $data.resetFilters, Label: $label('FilterDisplayControl_Reset'), Name: $dyn.value($data.Name) + '_ResetFilters'"></button>
        </div>
    </div>
</div>

<div id="FilterField" class="filterField FilterStringField editMode" data-dyn-bind="visible: $data.ShowFilterField, onPaste: $data.OnPaste">
    <div class="filterField-header">
        <div class="filterField-titleContainer" role="group" data-dyn-bind="
            attr: { 'aria-labelledBy': $data.Id + '_title'}">
            <div class="filterField-title" data-dyn-bind="
                id: $data.Id + '_title',
                sizing: { width: $dyn.layout.Size.content },
                text: $dyn.value($data.FieldLabel),
                title: $dyn.value($data.FieldLabel),
                vars: {$filterField: $data}">
            </div>
            <div data-dyn-role="MenuButton" class="editMode" data-dyn-bind="
                Label: $filterField.OperatorLabel,
                Enabled: $filterField.AllowEdit,
                ShownIndex: $filterField.ShownIndex,
                HasBeenOpened: $filterField.MenuDisplayed,
                Click: function() { $filterField.UpdateInitialShownIndex(); }">
                <div data-dyn-bind="foreach: $dyn.controls.FilterField.SupportedOperators($dyn.value($filterField.DataType), $dyn.value($filterField.FieldName))">
                    <button data-dyn-role="MenuItem" data-dyn-bind="
                        Label: $dyn.controls.FilterDisplay.GetOperatorLabel($data, $value($filterField.DataType)),
                        Click: function() { $filterField.SelectOperator($data); },
                        Selected: $dyn.computed( function () { return $dyn.value($filterField.ShownIndex) == $index;})"></button>
                </div>
            </div>
        </div>
        <div class="filterField-buttonContainer" data-dyn-bind="if: $dyn.value($data.AllowEdit) && !$dyn.value($data.DisableRemoveButton)">
            <button data-dyn-role="SymbolButton" data-dyn-bind="
                ImageType: 'Symbol',
                ImageName: 'Cancel',
                Label: $dyn.format($label('FilterDisplayControl_RemoveField'), $dyn.value($data.FieldLabel)),
                ButtonDisplay: 'ImageOnly',
                Click: function() { $filterDisplay && $filterDisplay.removeFilterExpression($dyn.value($data.DataSource)) },
                "></button>
        </div>
    </div>
    <!-- Based on the type of input role, one of the following is rendered -->
    <div data-dyn-bind="if: $dyn.value($data.InputRoleType)=='IsOneOf'">
        <div data-dyn-role="IsOneOfFilterFieldContent"></div>
    </div>
    <div data-dyn-bind="if: $dyn.value($data.InputRoleType)=='Input'">
        <div data-dyn-role="InputFilterFieldContent" data-dyn-bind="FilterField: $data"></div>
    </div>
    <div data-dyn-bind="if: $dyn.value($data.InputRoleType)=='Integer'">
        <div data-dyn-role="IntegerFilterFieldContent" data-dyn-bind="FilterField: $data"></div>
    </div>
    <div data-dyn-bind="if: $dyn.value($data.InputRoleType)=='Int64'">
        <div data-dyn-role="Int64FilterFieldContent" data-dyn-bind="FilterField: $data"></div>
    </div>
    <div data-dyn-role="Toolbar" data-dyn-bind="Visible: $data.ShowAddField">
        <div data-dyn-role="ToolbarGroup">
            <!-- This button is only shown if the field operator is 'IsOneOf' and it isn't using the optimized 'IsOneOf' filtering feature. It allows the user to add more values to the field. -->
            <button data-dyn-role="Button" data-dyn-bind="
                    ImageType: 'Symbol',
                    ImageName: 'Add',
                    Label: $label('FilterField_AddField'),
                    Click: function(){ $data.Values.push(''); }">
            </button>
        </div>
    </div>
</div>

<div id="IsOneOfFilterFieldContent" class="filterField-content">
    <div data-dyn-role="Input"
         data-dyn-bind="
            Label: $data.FilterField.FieldAriaLabel,
            Value: $data.CombinedValue,
            AllowEdit: $data.FilterField.AllowEdit,
            Name: $data.FilterField.Name + '_Input',
            Width: $dyn.layout.Size.large,
            LookupButton: $data.FilterField.ShowLookup,
            RequestPopup: $dyn.controls.FilterField.OnRequestPopup($data.FilterField),
            DisableAutoPresentLookup: true,
            TableId: $data.FilterField.TableId,
            FieldId: $data.FilterField.FieldId,
            paste_Value: $data.OnPasteValue,
            ShowLabel: false"></div>
    <div data-dyn-bind="if: $data.FilterField.ContainsMoreThanEmptyValue">
        <div data-dyn-role="FilterFieldPillList"></div>
    </div>
    <div class="filterField-isOneOfFooter" data-dyn-bind="if: $data.ContainsMoreThanCanBeDisplayed">
        <div class="filterField-isOneOfFooter-clearButtonContainer">
            <a data-dyn-role="AnchorButton"
                    data-dyn-bind="
                        Name: $data.FilterField.Name + '_ClearButton',
                        Label: $dyn.label('FilterField_ClearAll'),
                        Click: $data.ClearAllValues"></a>
        </div>
        <div class="filterField-isOneOfFooter-showValuesButtonContainer">
            <a data-dyn-role="AnchorButton"
                    data-dyn-bind="
                        Name: $data.FilterField.Name + '_ShowValuesButton',
                        ImageType: 'Symbol',
                        ImageName: $data.CappingToggleButtonSymbol,
                        Label: $data.CappingToggleButtonText,
                        HelpText: $data.CappingToggleButtonHelpText,
                        Click: $data.ToggleCapping"></a>
        </div>
    </div>
</div>

<div id="FilterFieldPillList">
    <ul class="filterField-pillList"
        role="listbox"
        tabindex="0"
        data-dyn-bind="
            keyDown: $data.keyDown,
            foreach: $data.Values,
            attr: {
                'aria-activedescendant': $data.Parent.FilterField.Name + '_Pill_' + $dyn.value($data.SelectedIndex)
            }">
        <li class="filterField-isOneOfPill"
            role="option"
            data-dyn-bind="
                id: $parent().Parent.FilterField.Name + '_Pill_' + $index,
                attr: {
                    'aria-label': $dyn.format($dyn.label('FilterField_PillAriaLabel'), $data)
                },
                selected: $index === $dyn.value($parent().SelectedIndex),
                click: function () { $dyn.setValue($parent(), 'SelectedIndex', $index); }">
            <div class="filterField-isOneOfPill-text"
                 data-dyn-bind="
                    sizing: { width: $dyn.layout.Size.content },
                    text: $data,
                    title: $data"></div>
            <div class="filterField-isOneOfPill-buttonContainer">
                <button data-dyn-role="SymbolButton"
                        data-dyn-bind="
                            ImageType: 'Symbol',
                            ImageName: 'Cancel',
                            Click: function () { $parent().DeletePillButtonClicked($index); },
                            Skip: true"></button>
            </div>
        </li>
    </ul>
</div>

<div
    id="InputFilterFieldContent"
    class="filterField-content"
    data-dyn-bind="
        vars: { '$filterField': $data.FilterField },
        foreach: {
            collection: $data.FilterField.Values,
            postRender: $data.FilterField.postRenderValues,
            setAriaAttributes: false
        }">
    <div data-dyn-role="Input" data-dyn-bind="
         Label: $filterField.FieldAriaLabel,
         FieldLabel: $filterField.FieldLabel,
         Value: $data,
         AllowEdit: $filterField.AllowEdit,
         Name: $filterField.Name + '_Input_' + $index,
         Width: $dyn.layout.Size.large,
         LookupButton: $filterField.ShowLookup,
         RequestPopup: $dyn.controls.FilterField.OnRequestPopup($filterField),
         DisableAutoPresentLookup: true,
         TableId: $filterField.TableId,
         FieldId: $filterField.FieldId,
         paste_Value: $dyn.controls.FilterField.paste_Value($filterField, $index),
         ShowLabel: false,
         IsFilterField: true">
    </div>
</div>

<div id="IntegerFilterFieldContent" class="filterField-content" data-dyn-bind="vars: { '$filterField': $data.FilterField }, foreach: {collection: $data.FilterField.Values, setAriaAttributes: false}">
    <div data-dyn-role="Integer" data-dyn-bind="
         Label: $filterField.FieldAriaLabel,
         Value: $data,
         AllowEdit: $filterField.AllowEdit,
         Alignment: 'Left',
         Name: $filterField.Name + '_Input_' + $index,
         Width: $dyn.layout.Size.large,
         ShowZero: true,
         AllowBlankValue: true,
         LookupButton: $filterField.ShowLookup,
         RequestPopup: $dyn.controls.FilterField.OnRequestPopup($filterField),
         DisableAutoPresentLookup: true,
         TableId: $filterField.TableId,
         FieldId: $filterField.FieldId,
         paste_Value: $dyn.controls.FilterField.paste_Value($filterField, $index),
         ShowLabel: false">
    </div>
</div>

<div id="Int64FilterFieldContent" class="filterField-content" data-dyn-bind="vars: { '$filterField': $data.FilterField }, foreach: {collection: $data.FilterField.Values, setAriaAttributes: false}">
    <div data-dyn-role="Int64" data-dyn-bind="
         Label: $filterField.FieldAriaLabel,
         Value: $data,
         AllowEdit: $filterField.AllowEdit,
         Alignment: 'Left',
         Name: $filterField.Name + '_Input_' + $index,
         Width: $dyn.layout.Size.large,
         ShowZero: true,
         AllowBlankValue: true,
         LookupButton: $filterField.ShowLookup,
         RequestPopup: $dyn.controls.FilterField.OnRequestPopup($filterField),
         DisableAutoPresentLookup: true,
         TableId: $filterField.TableId,
         FieldId: $filterField.FieldId,
         paste_Value: $dyn.controls.FilterField.paste_Value($filterField, $index),
         ShowLabel: false">
    </div>
</div>

<div id="QuickFilter" class="quickFilter" role="search" data-dyn-focus=".field"
     data-dyn-bind="keyDown: $data.keyDown,
                    keyUp: $data.keyUp,
                    visible: $data.Visible,
                    enabled: $data.Enabled,
                    attr: {
                        'data-dyn-placeholder': $dyn.label($dyn.format($dyn.value($data.PlaceholderText))),
                        'aria-owns': $data.Id + '_listbox',
                    },
                    sizing: $dyn.layout.sizing($data),
                    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
                    ariaLabelledBy: { byElementId: $data.Id + '_Input_label' }">
    <div data-dyn-role="Input"
         data-dyn-bind="Width: $data.LayoutWidth,
                        Name: $data.Name + '_Input',
                        Value: $data.InputValue,
                        Enabled: $data.Enabled,
                        TextChanged: $data.TextChanged,
                        showToolTip: false,
                        ShowLabel: false,
                        Label: $dyn.label($dyn.format($dyn.value($data.PlaceholderText))),
                        paste_Value: $data.paste_Value">
    </div>
    <button tabindex="-1" role="button" type="button" class="button quickFilter-applyButton" data-dyn-bind="
        enabled: $data.Enabled,
        click: $data.callApplyFilter,
        title: $label('QuickFilter_ApplyButtonTooltip'),
        superTooltip: $dyn.ui.superTooltip($data),"></button>
    <div data-dyn-bind="
           flyout: {
                target: $($element).siblings('.input_container').children('input'),
                flyout: $($element).children('.sysPopup'),
                show: $data.ShowFieldPicker,
                clickSubscriber: $data.flyoutClickSubscriber,
                positionResize: true,
                openOnClick: false,
                skipAria: true,
           }">
        <div role="presentation" class="sysPopup flyoutButton-flyOut quickFilter-dropdown layout-root-scope">
             <ul role='listbox'
			    data-dyn-bind="id: $data.Id + '_listbox',
                    ariaLabelledBy: { byElementId: $data.Id + '_Input_label'},
                    vars: { '$quickFilter': $data }, foreach: {collection: $data.getFieldsForFlyout()}">
                <li class="quickFilter-listItem flyout-menuItem" role="option" data-dyn-bind="
                    id: $parent().Id + '_listbox_item' + $index,
                    attr: {
                        'aria-posinset': $index + 1,
                        'aria-setsize': $length,
                        'aria-selected': $index == $dyn.value($quickFilter.selectedIndex)
                    },
                    click: function menuItemClicked() {
                        $dyn.setValue($quickFilter, 'Field', $data);
                        $quickFilter.selectedIndex($index);
                        $quickFilter.callApplyFilter();
                    }">
                    <span class='quickFilter-listFieldName' data-dyn-bind="text: $data"></span> "<span class='quickFilter-listFilterValue' data-dyn-bind="text: $dyn.value($quickFilter.TypedValue)"></span>"
                </li>
             </ul>
        </div>
    </div>
</div>
<!--Design Note:  Using classes is prefered to setting style directly in the templates.
    shell will be directly updating the display value to show and hide forms, and previous values are not saved.-->
<form id="Form" action="javascript:void(0)" onclick="javascript:void(0)" autocomplete="off" class="conductorContent fill-width fill-height layout-root-scope" 
role="form" data-dyn-container=".rootLayout" data-dyn-bind="
attr: { 'aria-label': $dyn.format('{0}: {1}', $dyn.value($data.FormCaption), $dyn.value($data.ParentTitleFields))},
layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
viewMode: $data.IsInViewMode,
focusIn: $data.FocusIn,
extendedStyle: $data.Style,
globalstyle: $dyn.options(function() { return { css: $value($data.GlobalStyle), active: $data.IsActive };})">
<div data-dyn-content="replace: '[data-dyn-role=AppBarSection]'" style="display: none;"></div>
<div data-dyn-role="MessageBar" data-dyn-controlname="MessageBar" class="messageBar layout-reflow-scope"></div>
<div class="formContainer" role="region" data-dyn-bind="
    attr: { 'aria-label': $dyn.format('{0}: {1}', $dyn.value($data.FormCaption), $dyn.value($data.ParentTitleFields)) },
    sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available },
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }">
    <div data-dyn-bind="
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available },
        layout: { arrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft, alignment: $dyn.layout.Alignment.top },">
        <div class="rootLevelSystemDefinedButtons" role="presentation" data-dyn-content="append: '.button_showList, .button_showFilters'">
        </div>
        <div data-dyn-content="replace: '[data-dyn-role=FilterPane]'"></div>
        <div data-dyn-content="replace: '.SidePanel'"></div>
        <div data-dyn-content="replace: '[data-dyn-role=FilterManager]'"></div>            
        <div class="rootContent" data-dyn-bind="
            sizing: $dyn.layout.sizing($data),
            layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }">
            <div class="formCaptionContainer" data-dyn-content="append:'[data-dyn-controlname=SystemDefinedManageViewFilters]'"
                data-dyn-bind="sizing: { width: $dyn.layout.Size.available },
                    formHeaderCreate: $dyn.ui.formHeaderCreate($data)">
            </div>
            <div class="rootLayout" data-dyn-content="append:':not([data-dyn-role=AppBarSection]):not([data-dyn-role=FactBox]):not([data-dyn-role=FilterPane]):not([data-dyn-role=FilterManager]):not(.button_showList):not(.button_showFilters):not([data-dyn-controlname=SystemDefinedManageViewFilters])'" data-dyn-bind="
                sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available },
                layout: $dyn.layout.containerBinding($data)">
            </div>
        </div>
        <div class="factBoxPane-container" role="complementary" data-dyn-bind="
        hidden: $data.NoShowableFactBoxes,
        keyDown: $data.FactBoxPanekeyDown,
        sizing: { width: $dyn.layout.Size.content, height: $dyn.layout.Size.available },      
        css: { 'factBoxPaneCollapsed': $dyn.value($data.FactBoxPaneCollapsed),
               'factBoxPaneExpanded': !$dyn.value($data.FactBoxPaneCollapsed)
        },
        layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }">
            <button data-dyn-role="Button" role="heading" aria-level="2" class="factBoxPane-toggleButton" data-dyn-controlname="FactBoxToggleExpand" 
                    data-dyn-bind="
                Label:  $dyn.label('FactBox_RegionTitle'), 
                Click: function (evt) { $data.ToggleFactBoxPane(evt)}, 
                ImageName:  $data.FactBoxPaneImageName, 
                ImageType: 'Symbol',
                ButtonDisplay: $dyn.ui.ButtonDisplay.textWithImageRight,
                Title: $dyn.value($data.FactBoxPaneTooltip),
                HelpText: $dyn.value($data.FactBoxPaneTooltip) + ' ' + $dyn.value($data.FactBoxPaneHelpText),
                AltText: $dyn.value($data.FactBoxPaneTooltip),
                keyDown: $data.EnterToggleFactBoxPane, 
                superTooltip: $dyn.ui.superTooltip($data),
                attr: { 'data-dyn-helptext': $dyn.value($data.FactBoxPaneHelpText),
                        'aria-expanded': !$dyn.value($data.FactBoxPaneCollapsed)}"
                >
            </button>
            <div class="factbox-pane layout-reflow-scope" data-dyn-content="append: '[data-dyn-controlname=FactBoxToggleExpand],[data-dyn-role=FactBox]'" data-dyn-bind="
                sizing: { width: $dyn.layout.Size.fixed, height: $dyn.layout.Size.available },
                layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
                hidden: $data.FactBoxPaneCollapsed">
            </div>
        </div>
    </div>
</div>
</form>

<div id="Dialog"
    role="dialog"
    action="javascript:void(0)"
    autocomplete="off"
    class="dialog-container layout-root-scope"
    aria-modal="true"
    data-dyn-container=".rootLayout" data-dyn-bind="
    sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available },
    ariaLabelledBy: { byElementId: $data.Id + '_header' }">
    <div class="modalBackground fadeInQuicker"
         onclick="void(0)"
         tabindex="-1"
         aria-hidden="true"></div>
    <!-- The onclick attribute is needed to make this element clickable on some touch devices, reference bug 908793.
    If it is not clickable, we can't dismiss the slider by clicking on the parent form. -->
    <div class="dialog-popup conductorContent fixed-width fixed-height"
         data-dyn-bind="layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
                        dialogSize: $data.DialogSize">
        <div class="dialog-popup-content"
             data-dyn-bind="extendedStyle: $data.Style,
                            focusIn: $data.FocusIn,
                            layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
                            sizing: $dyn.layout.sizing($data),
                            dynamicSizing: { height: true, width: false },
                            viewMode: $data.IsInViewMode">
            <div data-dyn-role="MessageBar" data-dyn-controlname="MessageBar" class="messageBar layout-reflow-scope"></div>
            <div class="dialog-buttons"
                 data-dyn-bind="sizing: { width: $dyn.layout.Size.available }">
                <button data-dyn-role="SymbolButton" class="dialog-helpButton ignore-first-focus" data-dyn-controlname="$Dialog-HelpButton"
                        data-dyn-bind="ImageType:'Symbol',
                                        ImageName:'Help',
                                        Visible: $data.shouldDisplayHelpIcon,
                                        Label: $label('Dialog_HelpToolTip'),
                                        Click: $data.openHelp"></button>
                <button data-dyn-role="SymbolButton" class="dialog-hideButton ignore-first-focus" data-dyn-controlname="$Dialog-HideButton"
                        data-dyn-bind="ImageType:'Symbol',
                                        ImageName:'Cancel',
                                        Visible: $data._canHide,
                                        Label: $label('Dialog_HideToolTip'),
                                        Click: function() { $data.hide(); }"></button>
            </div>
            <div class="dialog-header"
                 data-dyn-bind="sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.content }">
                <div data-dyn-content="append:'[data-dyn-controlname=SystemDefinedManageViewFilters]'"></div>
                <div class="dialog-caption mainInstruction" role="heading" aria-level="1"
                     data-dyn-bind="id: $data.Id + '_header', text: $data.Caption, sizing: { width: $dyn.layout.Size.available }"></div>
            </div>
            <div class="rootContent"
                 data-dyn-bind="sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available },
                                layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }">
                <div class="rootLayout rootLayout-dialog" data-dyn-content="append: ':not(.mainInstruction)'"
                     data-dyn-bind="sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available },
                                    layout: $dyn.layout.containerBinding($data)">
                </div>
            </div>
        </div>
    </div>
</div>

<div role="presentation" id="LightBox" action="javascript:void(0)" autocomplete="off" class="lightbox-container layout-root-scope" data-dyn-bind="visible: $data.Visible" data-dyn-container=".lightbox-content">
    <div class="modalBackground fadeInQuicker" aria-hidden="true" tabindex="-1"></div>
    <div role="presentation" class="popupShadow allowTextSelection conductorContent scaleUpIn" style="right: 0px; left: 0px; bottom: 0px; top: 0px; position: absolute; outline: 0px;">
        <div role="presentation" class="lightbox">
            <div class="rootContent rootContent-lightBox fill-height" role="dialog" aria-labelledby="titleField" aria-modal="true"
                 data-dyn-formname="SysBoxForm"
                 data-dyn-bind="layout: { arrangeMethod: $data.ArrangeMethod, alignment: $dyn.layout.Alignment.top }">
                 <div class="formCaption" data-dyn-bind="text: $data.Caption"></div>
                 <div class="lightbox-content" data-dyn-content="replace: '*'"></div>
            </div>
        </div>
    </div>
</div>

<div id="AvailableShortcutsLightBox" data-dyn-role="LightBox" class="shortcutsLightBox" data-dyn-bind="ArrangeMethod: $dyn.layout.ArrangeMethod.vertical, Caption: $data.headerText">
    <div data-dyn-role="Group" data-dyn-controlname="BodyGroup" data-dyn-bind="Width: $dyn.layout.Size.available, Height: $dyn.layout.Size.available">
        <span data-dyn-role="Label" id='titleField' class="titleField ignore-first-focus" data-dyn-bind="Text: $data.headerText, Width: $dyn.layout.Size.available"></span>
        <div data-dyn-role="Group" data-dyn-controlname="ShortcutGroup" data-dyn-bind="Columns: 3, Height: $dyn.layout.Size.available, Width: $dyn.layout.Size.available">
            <div data-dyn-role="Group" data-dyn-controlname="ElementActionsGroup" data-dyn-bind="Visible: $data.ElementActionsVisible, Label: $data.ElementActionsLabel">
                <div data-dyn-bind="inlineForeach: $data.shortcuts[$dyn.ui.ShortcutCategory.ElementAction]">
                    <div data-dyn-role="Group" data-dyn-bind="ArrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft, Breakable: false">
                        <span data-dyn-role="Label" data-dyn-bind="Text: $data.descriptionText, Width: '220px', Skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                        <span data-dyn-role="Label" data-dyn-bind="Text: $data.keyText, Width: '100px', Skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                    </div>
                </div>
            </div>
            <div data-dyn-role="Group" data-dyn-controlname="NavigateGroup" data-dyn-bind="Visible: $data.NavigateVisible, Label: $data.NavigateLabel">
                <div data-dyn-bind="inlineForeach: $data.shortcuts[$dyn.ui.ShortcutCategory.Navigate]">
                    <div data-dyn-role="Group" data-dyn-bind="ArrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft, Breakable: false">
                        <span data-dyn-role="Label" data-dyn-bind="Text: $data.descriptionText, Width: '220px', Skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                        <span data-dyn-role="Label" data-dyn-bind="Text: $data.keyText, Width: '100px', Skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                    </div>
                </div>
            </div>
            <div data-dyn-role="Group" data-dyn-controlname="ActOnDataGroup" data-dyn-bind="Visible: $data.ActOnDataVisible, Label: $data.ActOnDataLabel">
                <div data-dyn-bind="inlineForeach: $data.shortcuts[$dyn.ui.ShortcutCategory.ActOnData]">
                    <div data-dyn-role="Group" data-dyn-bind="ArrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft, Breakable: false">
                        <span data-dyn-role="Label" data-dyn-bind="Text: $data.descriptionText, Width: '220px', Skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                        <span data-dyn-role="Label" data-dyn-bind="Text: $data.keyText, Width: '100px', Skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                    </div>
                </div>
            </div>
            <div data-dyn-role="Group" data-dyn-controlname="CloseGroup" data-dyn-bind="Visible: $data.CloseVisible, Label: $data.CloseLabel">
                <div data-dyn-bind="inlineForeach: $data.shortcuts[$dyn.ui.ShortcutCategory.Close]">
                    <div data-dyn-role="Group" data-dyn-bind="ArrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft, Breakable: false">
                        <span data-dyn-role="Label" data-dyn-bind="Text: $data.descriptionText, Width: '220px', Skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                        <span data-dyn-role="Label" data-dyn-bind="Text: $data.keyText, Width: '100px', Skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                    </div>
                </div>
            </div>
            <div data-dyn-role="Group" data-dyn-controlname="OtherGroup" data-dyn-bind="Visible: $data.OtherVisible, Label: $data.OtherLabel">
                <div data-dyn-bind="inlineForeach: $data.shortcuts[$dyn.ui.ShortcutCategory.Other]">
                    <div data-dyn-role="Group" data-dyn-bind="ArrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft, Breakable: false">
                        <span data-dyn-role="Label" data-dyn-bind="Text: $data.descriptionText, Width: '220px', Skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                        <span data-dyn-role="Label" data-dyn-bind="Text: $data.keyText, Width: '100px', Skip: !$dyn.util.isEnhancedTabSequenceEnabled()"></span>
                    </div>
                </div>
            </div>
        </div>
        <div data-dyn-role="Group" data-dyn-controlname="FooterGroup" data-dyn-bind="ArrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft, Width: $dyn.layout.Size.available">
            <div data-dyn-role="Group" data-dyn-bind="Width: $dyn.layout.Size.available">
                <a data-dyn-role="HyperLink" data-dyn-bind="Text: $label('Framework_ViewAllProductShortcuts'), OpenInNewWindow: true, BaseUrl: 'https://docs.microsoft.com/en-us/dynamics365/unified-operations/fin-and-ops/get-started/shortcut-keys'"></a>
            </div>
            <button data-dyn-role="Button" data-dyn-bind="Label: $label('MessageBox_Close'), Click: $data.closeClicked"></button>
        </div>
    </div>
</div>

<div id="LightBoxMessage" action="javascript:void(0)" data-dyn-role="LightBox" data-dyn-bind="ActiveControl: $data.ActiveControl">
    <div data-dyn-role="MessageBox" class="messageBoxContainer" data-dyn-bind="
        Text: $data.Text,
        SecondaryText: $data.SecondaryText,
        ImageType: $data.ImageType,
        ImageName: $data.ImageName,
        Tooltip: $data.Tooltip,
        ShowActivityId: $data.ShowActivityId,
        ActivityId: $data.ActivityId,
        showYesButton      : $data.showYesButton,
        showYesToAllButton : $data.showYesToAllButton,
        showNoButton       : $data.showNoButton,
        showNoToAllButton  : $data.showNoToAllButton,
        showOkButton       : $data.showOkButton,
        showCancelButton   : $data.showCancelButton,
        showCloseButton    : $data.showCloseButton,
        showDiagnostic     : $data.showDiagnostic,
        callback: $data.callback">
    </div>
</div>

<div id="ProgressMessage" action="javascript:void(0)" data-dyn-role="LightBox" class="ProgressMessage">
    <div data-dyn-role="Group" data-dyn-controlname="MainGroup" data-dyn-bind="ArrangeMethod: $dyn.layout.ArrangeMethod.vertical">
        <h1 id="titleField"
            data-dyn-role="Label"
            class="titleField ignore-first-focus"
            data-dyn-controlname="TitleText"
            data-dyn-bind="title: $data.TitleText, Text: $data.TitleText, Width: $dyn.layout.Size.content, Skip: false"></h1>
        <div data-dyn-role="Image" data-dyn-controlname="ProgressImage" data-dyn-bind="Visible: !$data.DisableAnimation, Value: {Items: ['1', 'URL', $dyn.shell.rootPath + 'Resources/Images/Animation_FO_Transparent.gif']}, Skip: true"></div>
        <h2 data-dyn-role="Label"
            data-dyn-controlname="SecondaryText"
            class="ignore-first-focus"
            data-dyn-bind="Text: $dyn.label('ProgressMessage_Text'), Width: $dyn.layout.Size.content, Skip: false "></h2>
        <div role="presentation" aria-live="polite">
            <span data-dyn-role="Label"
                data-dyn-controlname="ProgressText"
                class="ignore-first-focus"
                data-dyn-bind="title: $data.ProgressText, Text: $data.ProgressText, Width: $dyn.layout.Size.content, Skip: false"></span>
        </div>
        <button data-dyn-role="Button" data-dyn-controlname="Cancel" data-dyn-bind="Label: $label('ProgressMessage_CancelText'), Click: function () { $data.CancelClicked(); $dyn.shell.dialogBack(); }"></button>
    </div>
</div>

<div id="TimeoutDialog" data-dyn-role="LightBox" action="javascript:void(0)">
    <div data-dyn-role="Image" data-dyn-controlname="icon" data-dyn-bind="Value: {Items: ['2', 'Symbol', $dyn.value($data.imageName), $dyn.value($data.altText)]}, Skip: true"></div>
    <div data-dyn-role="Group" data-dyn-controlname="MainGroup">
        <div data-dyn-role="Group" data-dyn-controlname="TextGroup">
            <h1 id="titleField" data-dyn-role="Label" data-dyn-controlname="TitleText" class="titleField ignore-first-focus" data-dyn-bind="Text: $data.title"></h1>
            <div class="message_withTimer">
                <span id="secondaryField" data-dyn-role="Label" data-dyn-controlname="SecondaryText" class="ignore-first-focus" data-dyn-bind="Text: $data.message, Width: $dyn.layout.Size.content, Skip: false "></span>
                <span id="timerField" data-dyn-role="Label" data-dyn-controlname="TimerValue" class="timerField ignore-first-focus" data-dyn-bind="Visible: $data.continueButtonVisible(), Text: $data.timeRemaining"></span>
            </div>
        </div>
        <div data-dyn-role="Group" data-dyn-controlname="ButtonGroup"
            data-dyn-bind="ArrangeMethod: $dyn.layout.ArrangeMethod.horizontalRight ">
            <button data-dyn-role="Button" data-dyn-controlname="Continue" data-dyn-bind="Visible: $data.continueButtonVisible(), Label: $label('TimeoutDialogWarning_Continue'), DefaultButton: true, Click: function () {$data.continue();}"></button>
            <button data-dyn-role="Button" data-dyn-controlname="SignOut" data-dyn-bind="Visible: $data.signoutButtonVisible(), Label: $label('TimeoutDialogWarning_Signout'), Click: function () {$data.logout();}"></button>
            <button data-dyn-role="Button" data-dyn-controlname="StartNew" data-dyn-bind="Visible: $data.reconnectButtonVisible(), Label: $label('TimeoutDialog_ReconnectButtonText'), DefaultButton: true, Click: function () { $data.reconnect();}"></button>
        </div>
    </div>
</div>

<div id="ConnectionErrorDialog" action="javascript:void(0)" data-dyn-role="LightBox" data-dyn-bind="ActiveControl: $data.ActiveControl, layout: { arrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft, alignment: $dyn.layout.Alignment.top }">
    <div data-dyn-role="Image" data-dyn-controlname="icon" data-dyn-bind="Value: {Items: ['2', 'Symbol', $dyn.value($data.imageName), $dyn.value($data.altText)]}, Skip: true"></div>
    <div data-dyn-role="Group" data-dyn-controlname="MainGroup">
        <div data-dyn-role="Group" data-dyn-controlname="TextGroup">
            <h1 id="titleField" data-dyn-role="Label" data-dyn-controlname="FormStaticTextControl1" class="titleField" data-dyn-bind="Text: $data.TitleText"></h1>
            <div class="DiagnosticDataContainer">
               <div data-dyn-role="Group" data-dyn-controlname="DiagnosticDataGroup" data-dyn-bind="
                Label: $data.groupLabel,
                FrameOptionValue: $data.groupFrameOption,
                FrameOptionButton:'Hide'">
                    <span data-dyn-role="Label" data-dyn-controlname="BrowserSessionActivityId" data-dyn-bind="Text: $data.BrowserSessionActivityId, Skip: false"></span>
                    <span data-dyn-role="Label" data-dyn-controlname="BrowserInteractionTimestamp" data-dyn-bind="Text: $data.BrowserInteractionTimestamp, Skip: false"></span>
                    <span data-dyn-role="Label" data-dyn-controlname="buildInformation" data-dyn-bind="Text: $data.buildInformation, Skip: false"></span>
               </div>
               <button data-dyn-role="Button" data-dyn-controlname="CopyDiagnosticsData" data-dyn-bind="Label: $dyn.label('Copy_Button'), ImageName: 'Copy', ImageType: 'Symbol', Click: function() { $dyn.util.copyMessageDiagnosticsToClipBoard($data); }"></button>
            </div>
        </div>
        <div data-dyn-role="Group" data-dyn-controlname="ButtonGroup">
            <button data-dyn-role="Button" data-dyn-controlname="Retry" data-dyn-bind="Label: $data.retryButtonText, Click: $data.retry, DefaultButton: true"></button>
        </div>
    </div>
</div>

<div id="MessageBox" data-dyn-bind="visible: $data.Visible, layout: { arrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft, alignment: $dyn.layout.Alignment.top }" data-dyn-context="">
    <div data-dyn-role="Image" data-dyn-controlname="icon" data-dyn-bind="visible: $dyn.value($data.ImageName) != '', Value: {Items: ['2', $dyn.value($data.ImageType), $dyn.value($data.ImageName), $dyn.value($data.Tooltip)]}, Skip: true"></div>
    <div data-dyn-role="Group" data-dyn-controlname="MainGroup">
        <div data-dyn-role="Group" data-dyn-controlname="TextGroup">
            <h1 id="titleField" data-dyn-role="Label" class="titleField" data-dyn-controlname="FormStaticTextControl1"
                  data-dyn-bind="title: $data.TitleText, Text: $data.TitleText, Skip: false"></h1>
            <h2 data-dyn-role="Label" data-dyn-controlname="SecondaryText"
                  data-dyn-bind="Text: $data.SecondaryText, Visible: $data.SecondaryText, Skip: false "></h2>
            <div data-dyn-role="ListBox" data-dyn-controlname="MultipleMessagesListBox"
                 data-dyn-bind="Items: $data.Messages,
                    Visible: $data.HasMultipleMessages,
                    Height:''"></div>
            <div class="DiagnosticDataContainer">
                <div data-dyn-role="Group" data-dyn-controlname="DiagnosticDataGroup" data-dyn-bind="
                    Visible: $data.showDiagnostic,
                    Label: $data.groupLabel,
                    FrameOptionValue: $data.groupFrameOption,
                    FrameOptionButton:'Hide'">
                        <span data-dyn-role="Label" data-dyn-controlname="BrowserSessionActivityId" data-dyn-bind="Text: $data.BrowserSessionActivityId, Skip: false"></span>
                        <span data-dyn-role="Label" data-dyn-controlname="BrowserInteractionTimestamp" data-dyn-bind="Text: $data.BrowserInteractionTimestamp, Skip: false"></span>
                        <span data-dyn-role="Label" data-dyn-controlname="buildInformation" data-dyn-bind="Text: $data.buildInformation, Skip: false"></span>
                        <div data-dyn-role="Group" data-dyn-bind="ArrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft, Visible: $data.ShowActivityId">
                            <div data-dyn-role="Label" data-dyn-bind="Text: $label('MessageBox_BrowserActivityId'), Skip: false"></div>
                            <div data-dyn-role="Label" data-dyn-controlname="ActivityId" data-dyn-bind="Text: $data.ActivityId, Skip: false"></div>
                        </div>
                </div>
                <button data-dyn-role="Button" data-dyn-controlname="CopyDiagnosticsData" data-dyn-bind="Visible: $data.showDiagnostic, Label: $dyn.label('Copy_Button'), ImageName: 'Copy', ImageType: 'Symbol', Click: function() { $dyn.util.copyMessageDiagnosticsToClipBoard($data); }"></button>
            </div>
        </div>
        <div data-dyn-role="Group" data-dyn-controlname="ButtonGroup" data-dyn-bind="ArrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft">
            <button data-dyn-role="Button" data-dyn-controlname="Yes" data-dyn-bind="Label: $label('MessageBox_Yes'), Visible: $data.showYesButton, Click: function() { $data.buttonClicked($dyn.controls.MessageBox.Button.Yes); }"></button>
            <button data-dyn-role="Button" data-dyn-controlname="YesToAll" data-dyn-bind="Label: $label('MessageBox_YesToAll'), Visible: $data.showYesToAllButton, Click: function() { $data.buttonClicked($dyn.controls.MessageBox.Button.YesToAll); }"></button>
            <button data-dyn-role="Button" data-dyn-controlname="No" data-dyn-bind="Label: $label('MessageBox_No'), Visible: $data.showNoButton, Click: function() { $data.buttonClicked($dyn.controls.MessageBox.Button.No); }"></button>
            <button data-dyn-role="Button" data-dyn-controlname="NoToAll" data-dyn-bind="Label: $label('MessageBox_NoToAll'), Visible: $data.showNoToAllButton, Click: function() { $data.buttonClicked($dyn.controls.MessageBox.Button.NoToAll); }"></button>
            <button data-dyn-role="Button" data-dyn-controlname="Ok" data-dyn-bind="Label: $label('MessageBox_Ok'), Visible: $data.showOkButton, Click: function() { $data.buttonClicked($dyn.controls.MessageBox.Button.Ok); }"></button>
            <button data-dyn-role="Button" data-dyn-controlname="Cancel" data-dyn-bind="Label: $label('MessageBox_Cancel'), Visible: $data.showCancelButton, Click: function() { $data.buttonClicked($dyn.controls.MessageBox.Button.Cancel); }"></button>
            <button data-dyn-role="Button" data-dyn-controlname="Close" data-dyn-bind="Label: $label('MessageBox_Close'), Visible: $data.showCloseButton, Click: function() { $data.buttonClicked($dyn.controls.MessageBox.Button.Close); }"></button>
        </div>
    </div>
</div>

<form id="Popup" action="javascript:void(0)" tabindex="-1" autocomplete="off" class="popupShadow sysPopup layout-root-scope lookup-popup" role="region" data-dyn-childform="true" data-dyn-container=".rootContent"
      data-dyn-bind="focusIn: $data.FocusIn,
      attr: {'aria-label': $dyn.label('Form_LookupForm')}">
    <div class="rootContent fill-width" data-dyn-bind="layout: $dyn.layout.containerBinding($data)" data-dyn-content="append: '*'"></div>
</form>

<form id="DropDialogPopup" action="javascript:void(0)" aria-modal="true" autocomplete="off" class="popupShadow sysPopup layout-root-scope dropdialog-popup" role="dialog" data-dyn-childform="true" data-dyn-container=".rootContent"
      data-dyn-bind="focusIn: $data.FocusIn, attr: { 'aria-label': $data.Caption }" >
    <div data-dyn-role="MessageBar" data-dyn-controlname="MessageBar" class="messageBar layout-reflow-scope"></div>
    <div class="mainInstruction" role="heading" aria-level="2" data-dyn-bind="text: $data.Caption, visible: $data.Caption"></div>
    <div class="rootContent" data-dyn-bind="layout: $dyn.layout.containerBinding($data)" data-dyn-content="append: '*'"></div>
</form>

<form id="Preview" action="javascript:void(0)" aria-modal="true" autocomplete="off" class="popupShadow popupView sysPopup preview preview-position layout-root-scope" role="dialog" data-dyn-bind="extendedStyle: $data.Style, label: $data.Caption, attr: { 'tabindex': '-1' }" data-dyn-container=".rootLayout" data-dyn-childform="true">
    <div class="preview-inner">
        <div class="rootContent rootContent-Preview">
            <div class="rootLayout" data-dyn-bind="layout: $dyn.layout.containerBinding($data)" data-dyn-content="append: ':not([data-dyn-role=AppBarSection]):not([data-dyn-role=FactBox])'"></div>
        </div>
    </div>
    <div class="preview-Beak preview-Beak-Down"></div>
</form>

<div id="Part" data-dyn-bind="
    extendedStyle: $data.Style,
    visible: $data.Visible,
    sizing: $dyn.layout.sizing($data),
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }" data-dyn-container="true">
    <div data-dyn-content="append: '*'" style="display: none;"></div>
    <form data-dyn-role="PartForm" data-dyn-stop-binding="true"></form>
</div>

<div id="DataFilter" style="display:none" data-dyn-bind="" data-dyn-container="true" data-dyn-content="append: '*'"></div>

<div id="DataFilterRange" style="display:none" data-dyn-bind=""></div>

<form id="PartForm" action="javascript:void(0)" autocomplete="off" class="partView-topContainer" data-dyn-bind="
    extendedStyle: $data.Style,
    label: ($value($data.Caption) != $value($data.FormName)) ? $data.Caption : undefined,
    focusIn: $data.FocusIn,
    sizing: $dyn.layout.sizing($data),
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },"
      data-dyn-container=".rootLayout" data-dyn-childform="true">
    <div class="rootContent" data-dyn-bind="
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available, ignoreSiblings: true },
        layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }">
        <div class="formCaption" data-dyn-bind="text: ($value($data.Caption) != $value($data.FormName)) ? $data.Caption : undefined"></div>
        <div data-dyn-content="append: '[data-dyn-role=FilterPane]'" data-dyn-bind="visible: false"></div>
        <div class="rootLayout rootLayout-partForm" data-dyn-content="append: ':not([data-dyn-role=AppBarSection])'" data-dyn-bind="
            sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available, ignoreSiblings: true },
            layout: $dyn.layout.containerBinding($data)">
        </div>
    </div>
    <div data-dyn-content="append: ':not([data-dyn-role=AppBarSection])'" style="display: none;"></div>
</form>

<div id="FactBox" class="section section-page layout-reflow-scope factbox-element" data-dyn-focus=".section-page-header" data-dyn-bind="
    visible: $value($data.Visible) && $value($data.Caption),
    sizing: { height: $dyn.layout.Size.content },
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }" data-dyn-container="true">
    <div data-dyn-content="append: '*'"></div>
    <div class="section-page-header" role="heading" aria-level="3" data-dyn-bind="
        id: $data.Id + '_header'">
        <button class="section-page-caption" tabindex="0" data-dyn-bind="
            id: $data.Id + '_caption',
            label: $data.Caption,
            text: { text: $dyn.value($data.Caption), emptyStr: '&nbsp;' /* Use non-breaking space to maintain height when using an empty string. */},
            click: $data.toggleFactBoxExpanded,
            keyDown: $data.keydown,
            skip: $dyn.options(function() { return { skip: $data.Skip, enabled: true }; }, $data.Updating),
            superTooltip: $dyn.ui.superTooltip($data),
            ariaExpanded: $data.Expanded,
            sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.content },
            layout: { arrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft },
            attr: { 'aria-controls': $data.Id + '_container'}">
        </button>
    </div>
    <div class="section-container" data-dyn-bind="
            visible: $data.Expanded,
            id: $data.Id + '_container',
            sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available },
            layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }">
        <form data-dyn-role="FactBoxForm" data-dyn-stop-binding="true" data-dyn-bind="
                Part: $control,
                Width: $dyn.layout.Size.available,
                Height: $dyn.layout.Size.content"></form>
    </div>
</div>

<form id="FactBoxForm" action="javascript:void(0)" autocomplete="off" data-dyn-bind="
    extendedStyle: $data.Style,
    label: $data.Caption,
    viewMode: $data.IsInViewMode,
    focusIn: $data.FocusIn,
    sizing: $dyn.layout.sizing($data),
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }"
      data-dyn-container="true" data-dyn-childform="true">
    <div data-dynamics-formstyle="FormPart" class="rootContent viewMode" data-dyn-bind="
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available },
        layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }">
        <div class="formCaption" data-dyn-bind="text: $data.Caption"></div>
        <div data-dyn-content="append: '[data-dyn-role=FilterPane]'" data-dyn-bind="visible: false"></div>
        <div class="rootLayout rootLayout-factBox" data-dyn-content="append: ':not([data-dyn-role=AppBarSection])'" data-dyn-bind="
                sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available },
                layout: $dyn.layout.containerBinding($data)">
        </div>
    </div>
</form>

<div id="PartLink" style="display: none;" data-dyn-lastvisible="false" data-dyn-bind="visible: $data.Visible">
</div>

<div id="Group" class="group" data-dyn-bind="
        extendedStyle: $data.Style,
        visible: $data.Visible,
        enabled: $data.Enabled,
        viewMode: $data.IsViewMode,
        focusIn: $data.focusin,
        focusOut: $data.focusout,
        attr: {
            'data-dyn-frametype': $data.FrameType,
            'role' : ($dyn.value($data.FrameOptionButton) != 'None' || $data.Label || $dyn.value($data.IsTabularControl)) ? 'group' :'presentation',
        },
        ariaLabelledBy: { byElementId: ($data.Label ? $data.Id + '_text' : $dyn.value($data.IsTabularControl) ? $dyn.value($data.TabularControlLabelId) : undefined)},
        sizing: $dyn.layout.sizing($data),
        layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
        verticalSplitter: $data.VerticalSplitter,
        horizontalSplitter: $data.HorizontalSplitter,
        breakable: $dyn.value($data.IsBreakable),
        breakableGroups: $dyn.options($dyn.layout.breakableGroupsOptions($data), $data.Updating),
        css: { 'group-hasFrameOptionButton': $dyn.value($data.FrameOptionCSS), 
                'no-caption-group': $dyn.value($data.hasNoCaptionCSS),
                'col1': $dyn.value($data.Columns) == 1}"
     data-dyn-container=".group_content">
    <div role="presentation" class="group_header" data-dyn-bind="
        click: {callBack: function() { $data.HeaderClicked(); }, stopPropagation: true},
        groupButton: $data.FrameOptionButton,
        visible: $dyn.value($data.FrameOptionButton) == 'None' ? $data.Label : true,
        layout: { arrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft },
        sizing: { width: $data.VerticalSplitter ? $dyn.layout.Size.available : $dyn.layout.Size.content },
        css: { 'hasFocus' : $data.HasFocus, 'radioButton': $dyn.value($data.FrameOptionButton) == 'Radio'}">
        <span class="group_title" data-dyn-bind="
            id: $data.Id + '_text',
            text: $data.Label,
            attr: { role: ($dyn.value($data.Label)) ? 'heading' : '' },
            ariaLevel: true,
            ariaLabelFor: $dyn.ui.ariaLabelFor($data.Id + $dyn.value($data.getLabelForId()), $data),
            skip: $dyn.options(function() { return { skip: !$dyn.util.isEnhancedTabSequenceEnabled() }; }, $data.Updating),
            sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available, ignoreSiblings: true },
            css: { 'radioButton-label': $dyn.value($data.FrameOptionButton) == 'Radio', 'focusable': $dyn.util.isEnhancedTabSequenceEnabled() }">
        </span>
    </div>
    <div role="presentation" class="group_content" data-dyn-bind="
	    visible: $data.Expanded,
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available, ignoreSiblings: true },
        layout: $dyn.layout.containerBinding($data)"
         data-dyn-content="append: '*'">
    </div>
</div>

<div id="Card" class="baseCard" contenteditable="false" data-dyn-bind="
        extendedStyle: $data.Style,
        visible: $data.Visible,
        enabled: $data.Enabled,
        layout: { arrangeMethod: $dyn.layout.ArrangeMethod.none },
         css: { 'group-hasFrameOptionButton': $dyn.value($data.FrameOptionCSS),
                'cardOptionalImage': $data.HasImage,
                'cardOptionalImage-symbol': $data.HasSymbol,
                'cardOptionalImage-caption': $data.HasCaption,
                'cardOptionalStatus': $data.HasFooter,
                'cardHasHeading': $data.HasHeading,
                'cardOptionalActions': $data.HasActions,
                'cardOptionalNotes': $data.HasNotes }"
     data-dyn-container=".card_content">
    <div class="card_content" data-dyn-bind="
	    visible: $data.Visible"
         data-dyn-content="append: '*'">
    </div>
</div>

<div id="Pivot" role="presentation" class="pivot-container layout-reflow-scope" data-dyn-container="true" data-dyn-bind="
    visible: $data.Visible,
    enabled: $data.Enabled,
    sizing: $dyn.layout.sizing($data, undefined, $data.LayoutMinHeight),
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
    dynamicSizing: { height: true, width: true },
    keyDown: $data.keyDown,
    verticalSplitter: $data.VerticalSplitter,
    horizontalSplitter: $data.HorizontalSplitter,
    css: { 'pivot-noTabs': !$value($data.ShowHeaders), 'container-hasBackground': $value($data.ShowHeaders)}">
    <div role="presentation" class="pivot-header" data-dyn-bind="visible: $data.ShowHeaders,
         sizing: { width: ($value($data.Width) == $dyn.layout.Size.available ? $dyn.layout.Size.available : $dyn.layout.Size.content) }">
        <ul class="pivot-list" role="tablist" data-dyn-bind="foreach: $data.Children">
            <li class="pivot-item" role="tab" data-dyn-bind="
                selected: $data.isActive,
                title: $data.Label,
                skip: $dyn.options(function() { return { skip: !$dyn.value($data.isActive), enabled: $data.Enabled }; }, $data.Updating),
                controlName: $data.Name + '_header',
                id: $data.Id + '_header',
                click: $data.Activate,
                keyDown: $parent().headerKeyDown,
                visible: $data.Visible,
                focus: $data.isActive,
                superTooltip: $dyn.ui.superTooltip($data),
                attr: {
                    'data-dyn-mappedtab': $data.Name,
                    'aria-controls': $data.Id + '_panel'
                }">
                <span class="pivot-label" data-dyn-bind="
                    text: { text: $dyn.value($data.Label), emptyStr: '&nbsp;' }, /* Use non-breaking space to maintain height when using an empty string. */">
                </span>
            </li>
        </ul>
        <button class="pivot-listOverflowPrevious pivot-listOverflowButton button dynamicsButton" type="button" tabindex="0" data-dyn-bind="
                attr:{
                    'aria-label': $dyn.label('Pivot_PreviousButton'),
                },
                Value: $dyn.label('Pivot_PreviousButton'),
                click: $data.MoveLeft,
                mouseDown: $data.MoveLeftContinue,
                mouseUp: $data.MouseUp"></button>
        <button class="pivot-listOverflowNext pivot-listOverflowButton button dynamicsButton" type="button" tabindex="0" data-dyn-bind="
                attr:{
                    'aria-label': $dyn.label('Pivot_NextButton'),
                },
                Value: $dyn.label('Pivot_NextButton'),
                click: $data.MoveRight,
                mouseDown: $data.MoveRightContinue,
                mouseUp: $data.MouseUp"></button>
    </div>
    <div data-dyn-content="replace: '*'"></div>
</div>

<div id="VerticalTabs" role="presentation" class="pivot-container verticalTab layout-reflow-scope" data-dyn-container="true" data-dyn-bind="
    visible: $data.Visible,
    enabled: $data.Enabled,
    keyDown: $data.keyDown,
    extendedStyle: $data.Style,
    sizing: $dyn.layout.sizing($data, undefined, $data.LayoutMinHeight),
    layout: { arrangeMethod: $dyn.value($data.DropListVisual) ? $dyn.layout.ArrangeMethod.vertical : $dyn.layout.ArrangeMethod.horizontalLeft, alignment: $dyn.layout.Alignment.top },
    verticalSplitter: $data.VerticalSplitter,
    horizontalSplitter: $data.HorizontalSplitter">
    <div role="presentation"  class="pivot-header verticalTab-pivot-header" data-dyn-bind="
        visible: $data.ShowHeaders,
        sizing: { width: $dyn.layout.Size.content,
                height: $dyn.value($data.DropListVisual) ? $dyn.layout.Size.content : $dyn.layout.Size.available }">
        <div data-dyn-bind="if: $dyn.value($data.DropListVisual)">
            <div data-dyn-role="MenuButton" class="pivot-dropListMenu" data-dyn-bind="Label: $data.ActiveItemLabel">
                <div data-dyn-bind="foreach: $data.Children">
                    <button data-dyn-role="MenuItem" data-dyn-bind="
                        Label: $data.Label,
                        id: $data.Id + '_button',
                        Visible: $data.Visible,
                        Click: function() { $data.Activate(); }">
                    </button>
                </div>
            </div>
        </div>
        <div data-dyn-bind="if: !$dyn.value($data.DropListVisual)">
            <ul class="pivot-list" role="tablist" data-dyn-bind="foreach: $data.Children">
                <li class="pivot-item" role="tab" data-dyn-bind="
                    visible: $data.Visible,
                    skip: $dyn.options(function() { return { skip: !$dyn.value($data.isActive), enabled: $data.Enabled }; }, $data.Updating),
                    text: $data.Label,
                    controlName: $data.Name + '_header',
                    id: $data.Id + '_header',
                    selected: $data.isActive,
                    click: $data.Activate,
                    focus: $data.isActive,
                    keyDown: $parent().headerKeyDown,
                    superTooltip: $dyn.ui.superTooltip($data),
                    enumAriaItems: $data.Items,
                    enumAriaSelection: $data.selectedIndex,
                    attr: {'data-dyn-mappedtab': $data.Name}"></li>
            </ul>
        </div>
    </div>
    <div class="tab-container" data-dyn-content="replace: '*'"></div>
</div>

<div id="DropList" role="presentation" class="pivot-container pivot-dropList layout-reflow-scope" data-dyn-container="true" data-dyn-bind="
    visible: $data.Visible,
    enabled: $data.Enabled,
    sizing: $dyn.layout.sizing($data, undefined, $data.LayoutMinHeight),
    dynamicSizing: { height: true, width: true },
    layout: { arrange: $dyn.layout.ArrangeMethod.vertical },
    verticalSplitter: $data.VerticalSplitter,
    horizontalSplitter: $data.HorizontalSplitter">
    <div data-dyn-role="MenuButton" class="pivot-dropListMenu" data-dyn-bind="Label: $data.ActiveItemLabel">
        <div data-dyn-bind="inlineForeach: $data.Children">
            <button data-dyn-role="MenuItem" data-dyn-bind="
                Label: $data.Label,
                id: $data.Id + '_button',
                Visible: $data.Visible,
                Click: function() { $data.Activate(); }"></button>
        </div>
    </div>
    <div data-dyn-content="replace: '*'"></div>
</div>


<div id="PivotItem" class="pivot-content" role="tabpanel" data-dyn-bind="
    label: $data.Label,
    enabled: $data.Enabled,
    visible: $data.isActive,
    id: $data.Id + '_panel',
    ariaLabelledBy: { byElementId: $data.Id + '_header', showLabel: $dyn.value($data._parent.ShowHeaders), removeIfBlank: true },
    sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available },
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }" data-dyn-container=".pivotItem-content">
    <div class="pivotItem-content" data-dyn-content="append: '*'" data-dyn-bind="
        visible: $data.Visible,
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available },
        layout: $dyn.layout.containerBinding($data)"></div>
</div>

<div id="Panorama" class="panoramaContainer" data-dyn-container="true" role="group" data-dyn-excludeFromHistory="true" data-dyn-content="append: '*'" data-dyn-bind="
    visible: $data.Visible,
    enabled: $data.Enabled,
    sizing: $dyn.layout.sizing($data, undefined, $data.LayoutMinHeight),
    attr: { 'data-dyn-showheaders': $data.ShowHeaders },
    layout: $dyn.layout.containerBinding($data),
    verticalSplitter: $data.VerticalSplitter,
    horizontalSplitter: $data.HorizontalSplitter,
    horizontalScrollWithWheel: true">
</div>

<div id="PanoramaItem" class="panoramaItem" data-dyn-container=".panoramaItem-content" role="group" data-dyn-bind="
    visible: $data.Visible,
    enabled: $data.Enabled,
    sizing: $dyn.layout.sizing($data),
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
    attr: { 'aria-labelledBy': $data.Id + '_title'}">
    <div class="panoramaItem-title" data-dyn-bind="
        skip: $dyn.ui.skip($data),
        id: $data.Id + '_title',
        attr: {
         role: ($value($data.LabelAction)) ? 'link' : 'heading'
        },
        ariaLevel: true,
        labelFor: $dyn.ui.labelFor($element.parentNode, $data, true, '&nbsp'),
        click: $data.HeaderClicked,
        keyDown: $data.keyDown,
        css: { 'panoramaItem-title-isBlank': $dyn.value($data.Label) === '' }"></div>
    <div class="panoramaItem-content" role="presentation" data-dyn-content="append: '*'" data-dyn-bind="
        sizing: $dyn.layout.sizing($data),
        layout: $dyn.layout.containerBinding($data)">
    </div>
</div>

<div id="Section" class="section" data-dyn-container="true" data-dyn-excludefromhistory="true" data-dyn-content="append: '*'"
    data-dyn-bind="
        visible: $data.Visible,
        enabled: $data.Enabled,
        keyDown: $data.keyDown,
        sizing: $dyn.layout.sizing($data, undefined, $data.LayoutMinHeight),
        dynamicSizing: { height: false, width: true },
        layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical, children: $value($data.Children) },
        verticalSplitter: $data.VerticalSplitter,
        horizontalSplitter: $data.HorizontalSplitter">
</div>

<div id="SectionPage" class="section-page layout-reflow-scope" data-dyn-container=".section-container"
     data-dyn-bind="
        css: { 'section-page-noncollapsible': $value($data.FastTabExpanded) == 'Always' },
        visible: $data.Visible,
        enabled: $data.Enabled,
        keyDown: $data.keyDown,
        sizing: {
            width: $dyn.layout.Size.available,
            height: ($value($data.FastTabExpanded) == 'Always') ? $dyn.layout.Size.available : $dyn.layout.Size.content,
            minFlexHeight: ($value($data.FastTabExpanded) == 'Always') ? '280px' : undefined,
        },
        layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical }">
    <div class="section-page-header" role="heading" data-dyn-bind="
        id: $data.Id + '_header',
        ariaLevel: true
        ">
        <button class="section-page-caption" tabindex="0" data-dyn-bind="
            id: $data.Id + '_caption',
            click: $data.Clicked,
            keyDown: $data.keyDown,
            skip: $dyn.options(function() { return { skip: $data.Skip, enabled: true }; }, $data.Updating),
            label: $dyn.value($data.Label),
            text: { text: $dyn.value($data.Label), emptyStr: '&nbsp;' /* Use non-breaking space to maintain height when using an empty string. */},
            superTooltip: $dyn.ui.superTooltip($data),
            ariaExpanded: $data.Expanded,
            sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.content },
            layout: { arrangeMethod: $dyn.layout.ArrangeMethod.horizontalLeft },
            attr: { 'aria-controls': $data.Id + '_container'}">
        </button>
        <div data-dyn-bind="sizing: { width: $dyn.layout.Size.content }">
            <div data-dyn-content="replace: '[data-dyn-role=SectionPageHeader]'"></div>
        </div>
    </div>
    <div class="section-container container-hasBackground" role="group" data-dyn-bind="
        visible: $data.Expanded,
        id: $data.Id + '_container',
        sizing: { width: $dyn.layout.Size.available, height: ($value($data.FastTabExpanded) == 'Always') ? $dyn.layout.Size.available : $dyn.layout.Size.content },
        dynamicSizing: { height: true, width: true, heightChanged: $data.heightChanged },
        layout: $dyn.layout.containerBinding($data),
        attr: { 'aria-labelledBy': $data.Id + '_caption' }"
        data-dyn-content="append: ':not([data-dyn-role=SectionPageHeader])'">
    </div>
</div>

<div id="SummaryField" data-dyn-bind="
     text: ($dyn.value($data.formattedValue) ? $dyn.value($data.formattedValue) : '--'),
     title: $dyn.format('{0}: {1}', $dyn.value($data.Label), ($dyn.value($data.formattedValue) ? $dyn.value($data.formattedValue) : $dyn.label('SummaryField_Empty'))),
     superTooltip: $dyn.ui.superTooltip($data),
     visible: $data.Visible,
     attr: {
            name: $data.Name,
            'aria-label': $dyn.format('{0}: {1}', $dyn.value($data.Label), ($dyn.value($data.formattedValue) ? $dyn.value($data.formattedValue) : $dyn.label('SummaryField_Empty'))),
           } ,
     skip: $dyn.options(function() { return { skip: !$dyn.util.isEnhancedTabSequenceEnabled() }; }, $data.Updating),
     link: $dyn.ui.summaryFieldLink($data)">
</div>

<div id="SectionPageHeader" class="section-page-summary" role="presentation" data-dyn-bind="
    sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.content },
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.horizontalRight }" data-dyn-container="true" data-dyn-content="append: { content: '*' }">
</div>


<div id="Table" class="listRoot table list-hasRendered" data-dyn-bind="
    visible: $data.Visible,
    focusIn: $data.FocusIn,
    keyDown: $data._keyDown,
    sizing: $dyn.layout.sizing($data, $data.LayoutMinWidth, $data.LayoutMinHeight, $data.HeightOverride),
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
    secondaryNavigation: {keyboard: $data.OnKeyboardSecondaryNavigation, mouse: $data.OnMouseSecondaryNavigation},
    verticalSplitter: $data.VerticalSplitter,
    horizontalSplitter: $data.HorizontalSplitter,
    attr: {
        role: $value($data.IsNoResultsMessageDisplayed) ? 'none' : 'grid',
        'aria-multiselectable': $value($data.IsMarkingEnabled) ? 'true' : 'false',
    },
    layoutCompleted: function () { $data.postRenderInternal(true); }"
     data-dyn-container=".list-prototype">
    <!-- Don't display the header until foreach has executed.-->
    <!-- Put children at top so they are available right away.  DataBind chilren is too noisy currently.  Other context tags clone the content, so we
        need a place to hide the physical children -->
    <div role="presentation" class="listHeader" data-dyn-bind="
        if: $data.ShowHeader,
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.content }">
        <div role="presentation" class="table_header" data-dyn-bind="focusOut: $data.headerFocusOut">
            <div role="row" class="listItem listAsTable-HeaderRow layout-reflow-scope" data-dyn-bind="
                 vars: { '$table': $data },
                 foreach: { collection: $data.ColumnHeaderMetadata, preRender: $data._headerPreRender, postRender: $data._headerPostRender, getIdentifier: $data._getHeaderId, reuseItems: true, setAriaAttributes: false }">
                <div class="listCell columnHeader" data-dyn-bind="visible: $data.Visible, css: {number: $dyn.value($data.IsNumber)}, attr: { 'data-dyn-columnname': $data.Name, 'data-dyn-explicitcolumnwidth': $dyn.value($data.Width)}">
                    <!--Note that jQuery UI resizable cannot resize THs directly and instead must operate against TH content. 
                        Used data attribute "data-colindex" instead of aria-colindex, since screen readers can incorrectly read aria-columnindex with some browsers.-->
                    <div class="columnHeaderWrapper" role="columnheader" data-dyn-bind="attr: {'data-colindex': $index+1, 'aria-label': $data.Label }, 
                         skip: $dyn.ui.controlOptions(function () { return { skip: $table.SkipColumnHeaders, enabled: $table.Enabled }; }, $table),
                         resizable: {handles: 'e', zIndex: 'auto', resize: $control.StartColumnHeaderResize, stop: $control.StopColumnHeaderResize}">
                        <div class="columnHeader-label" data-dyn-bind="text: $data.Label, textAlign: $data.Alignment"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="scrollRegion scrollingElement listScrollRegion" style="position: relative; overflow: auto;" data-dyn-bind="
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available, ignoreSiblings: true },
        attr: { 'aria-owns': $data.ListBoxIdentifier },
        scroll: $data.OnScroll">
        <div class="listView hasGlobalLayoutEvent" data-dyn-bind="
            vars: {'$list': $data},
            css: {
                isPrimaryNavigationSupported:  $data.NavigationEnabled,
                highlightActive: $data.HighlightActive,
                showRowLabels: $data.ShowRowLabels,
            },
            enabled: $data.Enabled,
            attr: {
                id: $data.ListBoxIdentifier,
                'data-dyn-gridlines': $value($data.GridLines)
            }">
            <!--No rows message should be located above lists so that the placeholder row/listItem doesn't vertically offset its position.-->
            <div class="list-No-Rows-Indicator" data-dyn-bind="visible: $data.IsNoResultsMessageDisplayed">
                <img class="list-No-Rows-IndicatorImage" tabindex="0" data-dyn-bind="
                attr: { 'src': $data.NoResultImage, 'aria-describedby': $data.Id + '_noRowsLabel' }">
                <span data-dyn-bind="id: $data.Id + '_noRowsLabel', text: $dyn.label('List_NoResultsMessage')"></span>
            </div>

            <!--The following is displayed in "Tabular" view mode. -->
            <div role="presentation" class="TabularView" data-dyn-isTable="true" data-dyn-bind="
                css: {
                    markingDisabled: function () { return !$dyn.value($data.IsMarkingEnabled); },
                    SimpleListView: $value($data.Mode) === $dyn.ui.ListMode.list,
                }">
                <div class="listBody"
                     data-dyn-content="append: {content: '*', mutator: $dyn.controls.Table.prototype._rowMutator}">
                </div>
            </div>
        </div>
    </div>
</div>

<div id="TableRowLabelsHeader" class="rowLabelContainer columnHeader rowLabelHeader" role="columnheader" data-dyn-bind="visible: $data.ShowRowLabels">
    <div class="rowLabelHeaderWrapper columnHeaderWrapper"></div>
</div>

<div id="RowTemplate_Table" class="rowTemplate listItem" data-dyn-container="true" role="row" class="listItem listAsTable-Row" data-dyn-bind="">
    <!--The following td represents the "check mark" column. -->
    <div class="rowLabelContainer listCell" role="gridcell" data-dyn-bind="visible: $list.ShowRowLabels, attr: { 'aria-label': $data._rowLabel }, skip: { skip: !$dyn.util.isEnhancedTabSequenceEnabled() }">
        <span class="listItemLabel" data-dyn-bind="text: $data._rowLabel"></span>
    </div>
    <!--The following td is repeated using 'wrap' to represent the different data columns. -->
    <div class="repeater-template" data-dyn-content="replace: {
                content: '*',
                mutator: $dyn.controls.Table.prototype._columnMutator
        }"></div>
</div>
<div id="List" role="grid" class="listRoot list-hasRendered layout-reflow-scope" data-dyn-bind="
    visible: $data.Visible,
    keyDown: $data.RowKeyDown,
    sizing: $dyn.layout.sizing($data, $data.LayoutMinWidth, $data.LayoutMinHeight, $data.HeightOverride),
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
    verticalSplitter: $data.VerticalSplitter,
    horizontalSplitter: $data.HorizontalSplitter,
    layoutCompleted: function () { $data._layoutCompleted(true); },
    css: {'list-column-wrap': $value($data.Width) === $dyn.layout.Size.available && $value($data.Mode) === $dyn.ui.ListMode.list && $value($data.GroupBy) === '',
          'listGroupView': $value($data.Width) === $dyn.layout.Size.available && $value($data.Mode) === $dyn.ui.ListMode.list && $value($data.GroupBy) !== '',
          'list-multiselectable':$data.IsMarkingEnabled,
          'listNoResults': $data.IsNoResultsMessageDisplayed,
          'list-listMode': $value($data.Mode) === $dyn.ui.ListMode.list,
          'list-tabularMode': $value($data.Mode) !== $dyn.ui.ListMode.list,
    },
    showMarkColumn: $data.IsSelectionIndicatorVisible,
    attr: {
        'aria-multiselectable': $value($data.IsMarkingEnabled) ? 'true': 'false',
        'data-dyn-visibleCols': $data.VisibleColumnCount
    },"
    data-dyn-container="true">
    <div role="presentation" class="listHeader" data-dyn-stop-binding="true" hidden data-dyn-bind="
        scroll: $data.headerScroll,
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.content }">
        <div role="presentation" class="table_header" data-dyn-bind="focusOut: $data.headerFocusOut">
            <div role="row" class="listItem listAsTable-HeaderRow layout-reflow-scope" data-dyn-bind="
                 vars: { '$grid': $data },
                 foreach: { collection: $data.RenderedHeaderMetadata, preRender: $data._headerPreRender, postRender: $data._headerPostRender, iterationCallback: $data._headerIterationCallback,
                            setAriaAttributes: false, getIdentifier: $data._getHeaderId, getVersion: $data._getHeaderVersion, reuseItems: true, updating: $dyn.ui.updating }">
                <div class="listCell columnHeader" data-dyn-focus=".columnHeaderWrapper" data-dyn-bind="
                    visible: $data.Visible,
                    textAlign: $data.Alignment,
                    css: { isNumber: $dyn.value($data.IsNumber), isImage: $dyn.value($data.IsImage), isFilterable: $dyn.value($data.IsFilterable), isSortable: $dyn.value($data.IsSortable), 'field-hasLookupButton': $dyn.value($data.IsLookupField) },
                    dir: $data.IsNumber ? 'ltr': '',
                    attr: { 'data-dyn-columnname': $data.Name, 'data-dyn-explicitcolumnwidth': $dyn.value($data.Width) }
                    ">
                    <!--Note that jQuery UI resizable cannot resize THs directly and instead must operate against TH content. -->
                    <div data-dyn-role="ColumnHeader" data-dyn-bind="Name: $data.Name, Skip: $dyn.util.headerSkip($data, $grid), Enabled: $data.Enabled, Index: $dyn.observable($index+1), ExecutePersonalizationCommand: $data.ExecutePersonalizationCommand, PersistPersonalization: $data.PersistPersonalization, Required: $data.Required"></div>
                </div>

            </div>
        </div>
    </div>
    <!--No rows message should be located above lists so that the placeholder row/listItem doesn't vertically offset its position.-->
    <div class="list-No-Rows-Indicator" data-dyn-bind="
         visible: $data.IsNoResultsMessageDisplayed, 
         sizing: { width: $dyn.layout.Size.available }">
        <img class="list-No-Rows-IndicatorImage" tabindex="0" data-dyn-bind="
            attr: { 'src': $data.NoResultImage, 'aria-labelledby': $data.Id + '_noRowsLabel' }">
        <span data-dyn-bind="
            id: $data.Id + '_noRowsLabel', 
            text: $data.getNoResultsMessage()"></span>
    </div>

    <div tabindex="-1" class="scrollRegion scrollingElement listScrollRegion" style="position: relative; overflow: auto;" data-dyn-bind="
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available, ignoreSiblings: true },
        scroll: $data.OnScroll,
        keyUp: $data.RowKeyUp,
        horizontalScrollWithWheel: { height: function() { return $data.GetHeightForHandler(); }, width: function() { return $data.GetScrollRegionWidth(); } }">

        <div role="presentation" class="listView hasGlobalLayoutEvent" data-dyn-bind="
            vars: {'$list': $data},
            css: {isPrimaryNavigationSupported:  $data.NavigationEnabled },
            enabled: $data.Enabled,
            event: { 'secondaryNavigation': $data.OnMouseSecondaryNavigation },
            attr: { id: $data.ListBoxIdentifier }">
            <div role="presentation" data-dyn-bind="
                css: {
                    SimpleListView: $value($data.Mode) === $dyn.ui.ListMode.list,
                    TabularView: $value($data.Mode) !== $dyn.ui.ListMode.list,
                },
                attr: {'data-dyn-gridlines': $value($data.GridLines)}">
                <div class="listBody" data-dyn-virtualcontext="true" data-dyn-bind="
                    captureClick: { captureRightClick: true, callBack: function(event) { $data.RowClicked(event); } },
                    focusIn: $data._focusIn,
                    list: { collection: $data.DataSource, selectedIndex: $data.SelectedIndex, cacheSize: $data.CacheSize, fetchedDataStartPosition: $data.FetchedDataStartPosition,
                     dataAbove: $data.DataAbove, dataBelow: $data.DataBelow, groupBy: $data.GroupBy, deferred: $data.AsyncRender, preRender: $data.PreRender,
                     postRender: $data.postRenderInternal, updating: $dyn.ui.updating, skipRenderDuringStaticLoading: true }">
                    <div data-dyn-content="append: '*'"></div>
                </div>
            </div>
        </div>
    </div>
    <div class="pagingButtons" data-dyn-bind="
        visible: $data.ArePagingButtonsVisible,
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.content }">
        <button data-dyn-role="Button" buttonstyle="Auto"
                data-dyn-bind="Click: $data.LoadPreviousPage,
                               Label: $dyn.label('Grid_Previous'),
                               ImageName:'Previous',
                               ImageType: 'Symbol',
                               ButtonDisplay: $dyn.ui.ButtonDisplay.textWithImageLeft,
                               attr: {'aria-label': $dyn.label('Grid_PreviousPage')},
                               Enabled: $dyn.computed(function() { return $data.CurrentPageIndex() > 0; })">
        </button>
        <button data-dyn-role="Button" buttonstyle="Auto"
                data-dyn-bind="Click: $data.LoadNextPage,
                               Label: $dyn.label('Grid_Next'),
                               ImageName: 'Next',
                               ImageType: 'Symbol',
                               ButtonDisplay: $dyn.ui.ButtonDisplay.textWithImageRight,
                               attr: {'aria-label': $dyn.label('Grid_NextPage')},
                               Enabled: $dyn.computed(function() { return $data.HasNextPage(); })">
        </button>
    </div>
</div>

<div id="ReactList" class="layout-reflow-scope react-listRoot" data-dyn-container="true" data-dyn-bind="
     keyUp: $data.keyUp,
     keyDown: $data.keyDown,
     mouseDown: $data.mouseDown,
     focusIn: $data.focusIn,
     visible: $data.Visible,
     sizing: $dyn.layout.sizing($data, $data.LayoutMinWidth, $data.LayoutMinHeight, $data.HeightOverride, $data.WidthOverride),
     layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
     verticalSplitter: $data.VerticalSplitter,
     horizontalSplitter: $data.HorizontalSplitter,">
    <div class="reactGrid" data-dyn-bind="sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available }"></div>
</div>

<div id="ListMarkAllHeader" role="presentation" class="markAllContainer columnHeaderSelectAll" data-dyn-explicitcolumnwidth="custom" data-dyn-bind="
                click: $data.ToggleMarkAllRecordsMode,
                css: {
                    'is-loading': $data._isLoading
                 }
                ">
    <div class="columnHeaderWrapper markingColumnHeader" role="columnheader">
        <span class="marked-record-checkbox checkMarkTarget"
              role="checkbox" data-dyn-bind="
                        checked: $data.MarkAllRecords,
                        skip: $dyn.util.markAllSkip($data),
                        attr: {'aria-label': $dyn.label('Grid_SelectAllRowsShortcut')}">
            <span class="checkMarkGlyph checkMarkTarget Checkmark-symbol"></span>
            <span class="boxGlyph checkMarkTarget"></span>
        </span>
    </div>
</div>

<div id="RowTemplate" class="rowTemplate listItem" data-dyn-container="true" role="row">
    <div role="gridcell" class="markContainer">
        <span class="marked-record-checkbox checkMarkTarget" role="checkbox" data-dyn-bind="
                    attr: {
                         'aria-label': $dyn.label('Grid_CurrentRowSelectionShortcut'),
                         'tabindex': $dyn.util.isEnhancedTabSequenceEnabled() ? '0' : '-1',
                    }">
            <span class="checkMarkGlyph checkMarkTarget unselectable Checkmark-symbol"></span>
            <span class="boxGlyph checkMarkTarget"></span>
        </span>
    </div>
    <div class="repeater-template" data-dyn-content="replace: { content: '*', mutator: $dyn.controls.List.prototype.columnMutator }"></div>
</div>

<div id="HeaderScrollDivPad" class="headerScrollDivPad" data-dyn-explicitcolumnwidth="custom">
</div>

<div id="ColumnHeader" class="columnHeaderWrapper" role="columnheader" data-dyn-bind="
     skip: $dyn.ui.skip($data),
     focusIn: $data.focusIn,
     focusOut: $data.focusOut,
     keyDown: $data.keyDown,
     resize: $data.columnHeaderResizeEventHandling,
     resizable: { handles: 'e', zIndex: 'auto', resize: $data.StartColumnHeaderResize, stop: $data.StopColumnHeaderResize },
     flyout: { skipAria: $data.skipAriaAttributes, flyout: $($element).children('.columnHeader-popup'), show: $data.ShowAddFilterDropDown, positionResize: true, clickSubscriber: $data.flyoutClickSubscriber },
     superTooltip: $dyn.ui.superTooltip($data),
     attr: { 'aria-sort': $data.sortDirection, 'data-colindex': $data.Index, 'aria-label': $data.Label }
     ">
    <div class="columnHeader-label" role="presentation" data-dyn-bind="text: $data.Label, textAlign: $data.Alignment"></div>
    <div class="columnHeader-indicator" aria-hidden="true" data-dyn-bind="css: {isSorted: $dyn.value($data.IsPrimarySort)}"></div>
    <div class="columnHeader-indicator" aria-hidden="true" data-dyn-bind="css: {isFiltered: $dyn.value($data.IsFiltered)}"></div>
    <div data-dyn-role="ColumnHeaderPopup" style="display: none;" class="columnHeader-popup sysPopup" data-dyn-stop-binding="true" hidden></div>
</div>

<div id="ColumnHeaderPopup" data-dyn-bind="Name: $data.controlName, keyDown: $data.processKeyDown">
    <div class="columnHeaderPopup-sort">
        <button data-dyn-role="Button" data-dyn-bind="Label: $data.AscendingLabel, Toggled: $data.AscendingToggle, Click: $data.SortAscending, Name:'Ascending_' + $data.controlName , ImageName: 'SortUp', ImageType: 'Symbol'"></button>
        <button data-dyn-role="Button" data-dyn-bind="Label: $data.DescendingLabel, Toggled: $data.DescendingToggle, Click: $data.SortDescending, ImageName: 'SortDown', Name:'Descending_' + $data.controlName, ImageType: 'Symbol'"></button>
    </div>
    <div class="filterFieldContainer" data-dyn-bind="vars: { '$outerContext': $data }, foreach: $data.FilterExpressions">
        <div data-dyn-role="FilterField"
             data-dyn-bind="DataSourceName: $data.FormDataSourceName,
                            FieldName: $data.FieldName,
                            AllowEdit: $data.IsEditable,
                            Operator: $data.Operator,
                            Values: $data.Values,
                            FieldCapability: $data.Capability,
                            Name: 'FilterField_' + $dyn.value($outerContext.controlName) + '_' + $dyn.value($data.FieldName),
                            RecordingReferences : $data.RecordingReferences,
                            DisableRemoveButton: true">
        </div>
    </div>
    <div class="columnHeaderPopup-buttons">
        <button data-dyn-role="Button" data-dyn-bind="Visible: $data.ShowApply, Enabled: $data.ButtonsEnabled, Click: $data.applyFilters, Label: $label('FilterDisplayControl_Apply'), Name: $dyn.value($data.controlName) + '_ApplyFilters', DefaultButton: true"></button>
        <button data-dyn-role="Button" data-dyn-bind="Visible: $data.ShowClear, Enabled: $data.ButtonsEnabled, Click: $data.resetFilters, Label: $label('FilterDisplayControl_Clear'), Name: $dyn.value($data.controlName) + '_ResetFilters'"></button>
    </div>
</div>

<div id="GroupTemplate" data-dyn-role="PanoramaItem" class="listGroupContainer panoramaItem">
    <h2 class="listGroupTitle"></h2>
    <div class="listGroupContent"></div>
</div>

<div id="HierarchicalGridBase" class="listRoot list-hasRendered layout-reflow-scope" data-dyn-bind="
    visible: $data.Visible,
    sizing: $dyn.layout.sizing($data, $data.LayoutMinWidth, $data.LayoutMinHeight, $data.HeightOverride),
    layout: { arrangeMethod: $dyn.layout.ArrangeMethod.vertical },
    verticalSplitter: $data.VerticalSplitter,
    horizontalSplitter: $data.HorizontalSplitter,
    layoutCompleted: function () { $data._layoutCompleted(true); },
    css: {'list-column-wrap': $value($data.Width) === $dyn.layout.Size.available && $value($data.Mode) === $dyn.ui.ListMode.list && $value($data.GroupBy) === '',
         'listGroupView': $value($data.Width) === $dyn.layout.Size.available && $value($data.Mode) === $dyn.ui.ListMode.list && $value($data.GroupBy) !== '',
         'list-multiselectable':$data.IsMarkingEnabled,
         'listNoResults': $data.IsNoResultsMessageDisplayed,
         'list-listMode': $value($data.Mode) === $dyn.ui.ListMode.list,
         'list-tabularMode': $value($data.Mode) !== $dyn.ui.ListMode.list,
     },
    showMarkColumn:$data.IsSelectionIndicatorVisible,
    'aria-multiselectable': $value($data.IsMarkingEnabled) ? 'true': 'false',
    attr: {
        'data-dyn-visibleCols': $data.VisibleColumnCount,
        'data-dyn-visibleRows': $data.VisibleRowCount,
        role: $value($data.IsNoResultsMessageDisplayed) ? 'none' : 'grid',
        },"
     data-dyn-container="true">
    <div role="presentation" class="listHeader" data-dyn-stop-binding="true" hidden data-dyn-bind="
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.content }">
        <div role="presentation" class="table_header">
            <div role="row" class="listItem listAsTable-HeaderRow layout-reflow-scope" tabindex="-1" data-dyn-bind="foreach: { collection: $data.RenderedHeaderMetadata,
                 preRender: $data._headerPreRender, postRender: $data._headerPostRender, getIdentifier: $data._getHeaderId, getVersion: $data._getHeaderVersion, reuseItems: true, updating: $dyn.ui.updating }">
                <div role="columnheader" class="listCell columnHeader" data-dyn-bind="
                    visible: $data.Visible,
                    textAlign: $data.Alignment,
                    css: { isNumber: $dyn.value($data.IsNumber), isFilterable: $dyn.value($data.IsFilterable), isSortable: $dyn.value($data.IsSortable), 'field-hasLookupButton': $dyn.value($data.IsLookupField)},
                    attr: { 'data-dyn-columnname': $data.Name, 'data-dyn-explicitcolumnwidth': $dyn.value($data.Width), 'aria-sort': $dyn.util.enumName($dyn.value($data.IsSorted), $dyn.ui.SortDirection)}
                    ">
                    <!--Note that jQuery UI resizable cannot resize THs directly and instead must operate against TH content. -->
                    <div data-dyn-role="HierarchicalGridBaseColumnHeader" data-dyn-bind="Name: $data.Name"></div>
                </div>

            </div>
        </div>
    </div>
    <!--No rows message should be located above lists so that the placeholder row/listItem doesn't vertically offset its position.-->
    <div class="list-No-Rows-Indicator" data-dyn-bind="visible: $data.IsNoResultsMessageDisplayed, sizing: { width: $dyn.layout.Size.available }">
        <img class="list-No-Rows-IndicatorImage" data-dyn-bind="
                attr: { 'src': $data.NoResultImage }">
            <span data-dyn-bind="text: $dyn.label('List_NoResultsMessage')"></span>
        </div>

    <div role="application" tabindex="-1" class="scrollRegion scrollingElement listScrollRegion" style="position: relative; overflow: auto;" data-dyn-bind="
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.available, ignoreSiblings: true },
        scroll: $data.OnScroll,
        keyDown: function (event) { $data.RowKeyDown(event); },
        attr: {'aria-owns': $data.ListBoxIdentifier, 'aria-activedescendant': $data.ListBoxIdentifier},
        horizontalScrollWithWheel: true">

        <div role="listbox" class="listView hasGlobalLayoutEvent" data-dyn-bind="
            vars: {'$list': $data},
            css: {isPrimaryNavigationSupported:  $data.NavigationEnabled },
            enabled: $data.Enabled,
            event: { 'secondaryNavigation': $data.OnMouseSecondaryNavigation },
            attr: {id: $data.ListBoxIdentifier }">
            <div role="presentation"  data-dyn-bind="
                css: {
                    SimpleListView: $value($data.Mode) === $dyn.ui.ListMode.list,
                    TabularView: $value($data.Mode) !== $dyn.ui.ListMode.list,
                },
                attr: {'data-dyn-gridlines': $value($data.GridLines)}">
                <div class="listBody" data-dyn-virtualcontext="true" data-dyn-bind="
                    captureClick: { captureRightClick: true, callBack: function(event) { $data.RowClicked(event); } },
                    focusIn: $data._focusIn,
                    hierarchicalgridbase: { collection: $data.DataSource, selectedIndex: $data.SelectedIndex, cacheSize: $data.CacheSize, fetchedDataStartPosition: $data.FetchedDataStartPosition,
                     dataAbove: $data.DataAbove, dataBelow: $data.DataBelow, groupBy: $data.GroupBy, deferred: $data.AsyncRender, preRender: $data.PreRender,
                     postRender: $data.postRenderInternal, renderPlaceholderRow: true, updating: $dyn.ui.updating, skipRenderDuringStaticLoading: true, scrollContainer: $(element).find('.listScrollRegion')}">
                    <div data-dyn-content="append: '*'"></div>
                </div>
            </div>
        </div>
    </div>
    <div class="pagingButtons" data-dyn-bind="
        visible: $data.ArePagingButtonsVisible,
        sizing: { width: $dyn.layout.Size.available, height: $dyn.layout.Size.content }">
        <button data-dyn-role="Button" buttonstyle="Auto"
                data-dyn-bind="Click: $data.LoadPreviousPage,
                               Label: $dyn.label('Grid_Previous'),
                               ImageName:'Previous',
                               ImageType: 'Symbol',
                               ButtonDisplay: $dyn.ui.ButtonDisplay.textWithImageLeft,
                               attr: {'aria-label': $dyn.label('Grid_PreviousPage')}">
        </button>
        <button data-dyn-role="Button" buttonstyle="Auto"
                data-dyn-bind="Click: $data.LoadNextPage,
                               Label: $dyn.label('Grid_Next'),
                               ImageName: 'Next',
                               ImageType: 'Symbol',
                               ButtonDisplay: $dyn.ui.ButtonDisplay.textWithImageRight,
                               attr: {'aria-label': $dyn.label('Grid_NextPage')}">
        </button>
    </div>
</div>

<div id="HierarchicalGridBaseMarkAllHeader" role="columnheader" class="markAllContainer columnHeaderSelectAll" data-dyn-explicitcolumnwidth="custom" data-dyn-bind="
                click: $data.ToggleMarkAllRecordsMode,

                ">
    <div class="columnHeaderWrapper">
        <span class="marked-record-checkbox checkMarkTarget" role="checkbox"
              aria-live="assertive" data-dyn-bind="
                        checked: $data.MarkAllRecords,
                        attr: {'aria-label': $dyn.label('List_DefaultCheckBoxText')}">
            <span class="checkMarkGlyph checkMarkTarget"></span>
            <span class="boxGlyph checkMarkTarget"></span>
        </span>
    </div>
</div>

<div id="HierarchicalGridBaseRowTemplate" class="rowTemplate listItem" data-dyn-container="true" role="option" tabindex="-1" >
    <div class="markContainer" role="gridcell">
        <span class="marked-record-checkbox checkMarkTarget" tabindex="-1" role="checkbox" aria-live="assertive" data-dyn-bind="
                    attr: {'aria-label': $dyn.label('List_DefaultCheckBoxText')}">
            <span class="checkMarkGlyph checkMarkTarget unselectable"></span>
            <span class="boxGlyph checkMarkTarget"></span>
        </span>
    </div>
    <div class="repeater-template" data-dyn-content="replace: { content: '*', mutator: $dyn.controls.List.prototype.columnMutator }"></div>
</div>

<div id="HierarchicalGridBaseColumnHeader" class="columnHeaderWrapper" role="columnheader" aria-haspopup="true" tabindex="-1" data-dyn-bind="
     focusIn: $data.focusIn,
     resizable: {handles: 'e', zIndex: 'auto', resize: $data.StartColumnHeaderResize, stop: $data.StopColumnHeaderResize},
     flyout: { flyout: $($element).children('.columnHeader-popup'), show: $data.ShowAddFilterDropDown, positionResize: true, clickSubscriber: $data.flyoutClickSubscriber},
     title: $data.Label
     ">
    <div class="columnHeader-label" data-dyn-bind="text: $data.Label, textAlign: $data.Alignment"></div>
    <div class="columnHeader-indicator" data-dyn-bind="css: {isSorted: ($dyn.value($data.IsSorted) == 0 || $dyn.value($data.IsSorted) == 1)}"></div>
    <div class="columnHeader-indicator" data-dyn-bind="css: {isFiltered: $dyn.value($data.IsFiltered)}"></div>
    <div data-dyn-role="HierarchicalGridBaseColumnHeaderPopup" class="columnHeader-popup sysPopup" data-dyn-bind="Name: $data.Name, keyDown: $data.processKeyDown" data-dyn-stop-binding="true" hidden> </div>
</div>

<div id="HierarchicalGridBaseColumnHeaderPopup" aria-live="polite" aria-relevant="all" aria-atomic="true">
    <div class="columnHeaderPopup-sort">
        <button data-dyn-role="Button" data-dyn-bind="Label: $data.AscendingLabel, Toggled: $data.AscendingToggle, Click: $data.SortAscending, Name:'Ascending_' + $data.Name , ImageName: 'Up', ImageType: 'Symbol'"></button>
        <button data-dyn-role="Button" data-dyn-bind="Label: $data.DescendingLabel, Toggled: $data.DescendingToggle, Click: $data.SortDescending, ImageName: 'Down', Name:'Descending_' + $data.Name, ImageType: 'Symbol'"></button>
    </div>
    <div data-dyn-bind="vars: { '$outerContext': $data }, foreach: $data.FilterExpressions">
        <div data-dyn-role="FilterField"
             data-dyn-bind="DataSourceName: $data.FormDataSourceName,
                            FieldName: $data.FieldName,
                            AllowEdit: $data.IsEditable,
                            Operator: $data.Operator,
                            Values: $data.Values,
                            FieldCapability: $data.Capability,
                            Name: 'FilterField_' + $dyn.value($outerContext.Name) + '_' + $dyn.value($data.FieldName),
                            RequestLookupForm: $outerContext.RequestLookupForm,
                            RecordingReferences : $data.RecordingReferences,
                            DisableRemoveButton: true">
        </div>
    </div>
    <div class="columnHeaderPopup-buttons">
        <button data-dyn-role="Button" data-dyn-bind="Visible: $data.ShowApply, Enabled: $data.ButtonsEnabled, Click: $data.applyFilters, Label: $label('FilterDisplayControl_Apply'), Name: $dyn.value($data.Name) + '_ApplyFilters'"></button>
        <button data-dyn-role="Button" data-dyn-bind="Visible: $data.ShowClear, Enabled: $data.ButtonsEnabled, Click: $data.resetFilters, Label: $label('FilterDisplayControl_Clear'), Name: $dyn.value($data.Name) + '_ResetFilters'"></button>
    </div>
</div>

<div id="HierarchicalGridBaseGroupTemplate" data-dyn-role="PanoramaItem" class="listGroupContainer panoramaItem">
    <h2 class="listGroupTitle"></h2>
    <div class="listGroupContent"></div>
</div>

﻿<div id="TaskRecorderPane" data-dyn-role="Dialog" data-dyn-bind="
       Caption: $label('TaskRecorder_PaneTitle'),
       Width: $dyn.layout.Size.available ,
       Height: $dyn.layout.Size.available,
       IsInViewMode: true,
       disposeOnClose: false,
       RequestClose: $dyn.util.emptyfunction" data-dyn-context="new $dyn.ax.TaskRecorderPane()">
    <div id=" taskrecorder_steps" data-dyn-role="Part" data-dyn-bind="
        RunMode:'Local',
        Visible:true,
        Width: $dyn.layout.Size.available,
        Height: $dyn.layout.Size.available,
        ObjectName: 'SysTaskRecorderPane',
        InitPartForm: $dyn.serverForm.serializers.InitPartForm.deserialize(),
        CreatePartForm: $dyn.serverForm.serializers.CreatePartForm.deserialize(), ">
    </div>
</div>

<div id="TaskRecorderState" style="display:none" data-dyn-bind=""></div>

<div id="WrappedTextControl" class="wrappedTextControl">
    <a id="ClickableText" class="wrappedTextControl-link" data-dyn-bind="
        visible:$dyn.computed(function() {return $dyn.value($data.IsLink) == 1;}),
        readonlyLink: { click: $data.Click, showLink: true },
        text:$data.Text,
        skip: $dyn.ui.skip($data)"></a>
    <span class="wrappedTextControl-text" data-dyn-bind="
        visible:$dyn.computed(function() {return $dyn.value($data.IsLink)==0;}),
        text:$data.Text,
        skip: $dyn.ui.skip($data)"></span>
</div>

<div id="WrappedTextControlCell" class="wrappedTextControl">
    <a id="ClickableText" class="wrappedTextControl-link" data-dyn-bind="
        visible:$dyn.computed(function() {return $dyn.value($data.IsLink) == 1;}),
        readonlyLink: { click: $data.Click, showLink: true },
        text:$data.Text"></a>
    <span class="wrappedTextControl-text" data-dyn-bind="
        visible:$dyn.computed(function() {return $dyn.value($data.IsLink)==0;}),
        text:$data.Text"></span>
</div>

<div id="TaskGuideDocumentViewer" data-dyn-bind="">
    <table id="TaskGuideContent" class="taskGuidePane-documentControl"></table>
</div>

<table>
    <tr id="TaskRowElement">
        <td colspan="4" id="TaskStepRow">
            <span class="taskGuideContent-taskRowElement"></span>
        </td>
    </tr>
</table>

<table>
    <tr id="TaskStepRowElement" class="taskGuideContent-stepRowElement">
        <td colspan="2" class="taskGuideContent-stepRowElement-td"></td>
        <td id="TaskStepRowNo" class="taskGuideContent-stepRowElement-td taskGuideContent-stepNo"></td>
        <td id="TaskStepRowDescription" class="taskGuideContent-stepRowElement-td">
            <span class="taskGuideContent-stepRowElement-span"></span>
        </td>
    </tr>
</table>

<table>
    <tr id="StepRowElement">
        <td id="StepRowNo" class="taskGuideContent-stepRowElement-td  taskGuideContent-stepNo"></td>
        <td colspan="3" id="StepRowDescription" class="taskGuideContent-stepRowElement-td">
            <span class="taskGuideContent-stepRowElement-span"></span>
        </td>
    </tr>
</table>

<div id="TaskRecorderStepAction" class="taskRecorder-stepAction" data-dyn-bind="width: $data.LayoutWidth, visible: $dyn.computed(function(){ return $dyn.value($data.Visible) && $dyn.value($data.CanEdit) != 0 }) ">
    <a data-dyn-bind="readonlyLink: { click: $data.EditStep, showLink: true }, title: $dyn.label('TaskRecorder_EditStep')">
        <div data-dyn-role="Image" data-dyn-controlname="annotation" data-dyn-bind="Value: $data.icon"></div>
    </a>
</div>

<div id="TaskRecorderToolbar" class="taskRecorderToolbar binding-focusRegion" data-dyn-focus-region="TaskRecorderToolbar" data-dyn-bind="focusIn: $dyn.shell.taskRecorderFocusHandler">
    <div class="taskRecorderToolbar-recorderState">
        <button class="taskRecorderToolbar-recordingButton" data-dyn-role="Button" data-dyn-bind="
                ButtonDisplay: $dyn.ui.ButtonDisplay.imageOnly,
                ImageType: 'Symbol',
                ImageName: 'Circle',
                Visible: $dyn.computed(function(){ return $dyn.value($dyn.ax.taskRecording.taskGuidePlaybackState) === false; })"></button>
        <button class="taskRecorderToolbar-playbackButton" data-dyn-role="Button" data-dyn-bind="
                ButtonDisplay: $dyn.ui.ButtonDisplay.imageOnly,
                ImageType: 'Symbol',
                ImageName: 'PlaySolid',
                Visible: $dyn.computed(function(){ return $dyn.value($dyn.ax.taskRecording.taskGuidePlaybackState) === true; })"></button>
    </div>
    <div class="taskRecorderToolbar-stepContextList">
        <span class="taskRecorderToolbar-stepContext" data-dyn-role="Label" data-dyn-bind="Text: $dyn.ax.taskRecording.currentTask"></span>
    </div>
    <div class="taskRecorderToolbar-recorderOptions">
        <button id="railsModeLock" class="taskRecorderToolbar-taskRecorderPane" data-dyn-role="Button" data-dyn-bind="Click:$dyn.ax.taskRecording.SwitchRailsModeOn,
                    ImageType: 'Symbol',
                    ImageName: 'Lock',
                    Label:$dyn.label('TaskRecorder_SwitchRailsModeOn'),
                    title:$dyn.label('TaskRecorder_SwitchRailsModeOn_ToolTip'),
                    ButtonDisplay:$dyn.ui.ButtonDisplay.textWithImageLeft,
                    Visible: $dyn.computed(function(){ return ($dyn.value($dyn.ax.taskRecording.taskGuidePlaybackState) && $dyn.value($dyn.ax.taskRecording.taskGuideRailsMode) === false); })"></button>
        <button id="railsModeUnlock" class="taskRecorderToolbar-taskRecorderPane" data-dyn-role="Button" data-dyn-bind="Click:$dyn.ax.taskRecording.SwitchRailsModeOff,
                    ImageType: 'Symbol',
                    ImageName: 'Unlock',
                    Label:$dyn.label('TaskRecorder_SwitchRailsModeOff'),
                    title:$dyn.label('TaskRecorder_SwitchRailsModeOff_ToolTip'),
                    ButtonDisplay:$dyn.ui.ButtonDisplay.textWithImageLeft,
                    Visible: $dyn.ax.taskRecording.taskGuideRailsMode"></button>
        <button id="taskRecorderStop" class="taskRecorderToolbar-taskRecorderPane" data-dyn-role="Button" data-dyn-bind="Click:$dyn.ax.taskRecording.stopSession,
                ImageType: 'Symbol',
                ImageName: 'Stop',
                Label:$dyn.label('TaskRecorder_Stop'),
                ButtonDisplay:$dyn.ui.ButtonDisplay.textWithImageLeft"></button>
        <button id="taskRecorderOpenPane" class="taskRecorderToolbar-taskRecorderPane" data-dyn-role="Button" data-dyn-bind="Click:$dyn.ax.taskRecording.toolbarOpenPane,
                ImageType: 'Symbol',
                ImageName: 'BulletedList',
                Label: $dyn.computed(function(){ return $dyn.value($dyn.ax.taskRecording.taskGuidePlaybackState) ? $dyn.label('TaskGuide_ShowSteps') : $dyn.label('TaskRecorder_OpenPane'); }),
                ButtonDisplay:$dyn.ui.ButtonDisplay.textWithImageLeft"></button>
    </div>
</div>

<div id="TaskGuideStep" class="taskGuideStep" data-dyn-bind="">
    <button data-dyn-role="Button" data-dyn-bind="
            ImageName: 'More',
            ImageType: 'Symbol',
            Click: $data.ToggleGuidedStep,
            Visible: $data.GuidedStepCollapsed,
            Title: $label('TaskGuidesStep_ExpandTitle')"
            class="taskGuide-popupButton"></button>
    <div data-dyn-bind="visible: $data.GuidedStepVisible">
        <span data-dyn-role="Label" data-dyn-bind="Visible: $data.HeaderVisible, Text: $data.Header" class="taskGuide-popupTitle taskGuide-popupTitleLabel taskGuide-popupHeader"></span>
        <div data-dyn-bind="" class="taskGuide-popupTitle">
            <div data-dyn-bind="" class="taskGuide-popupTitleBody">
                <div data-dyn-role="Image" class="taskGuide-HelpImage"
                      data-dyn-controlname="icon"
                      data-dyn-bind="Value: $data.Image, Visible: $data.ImageVisible"></div>
                <div data-dyn-bind="" class="taskGuide-popupTitleText">
                    <span data-dyn-role="Label" data-dyn-bind="Visible: $data.TitleVisible, Text: $data.Title" class="taskGuide-popupTitleLabel taskGuide-popupSpan"></span>
                    <span data-dyn-role="Label" data-dyn-bind="Visible: $data.StepAndTitleVisible" class="taskGuide-popupSpan"></span>
                    <span data-dyn-role="Label" data-dyn-bind="Visible: $data.StepVisible, Text: $data.Step" class="taskGuide-popupStepLabel taskGuide-popupSpan"></span>
                </div>
                <button data-dyn-role="Button" data-dyn-bind="
                    ImageName: 'Hide',
                    ImageType: 'Symbol',
                    Visible: $data.ShowMinimizeButton,
                    Click: $data.ToggleGuidedStep,
                    Title: $label('TaskGuidesStep_CollapseTitle')" class="taskGuide-popupButton"></button>
            </div>
            <div data-dyn-bind="visible: $data.ConfirmInfoStepVisible" class="taskGuide-popupInfoConfirm">
                <button data-dyn-role="Button" data-dyn-bind="
                Click: $data.SkipGuidedStep,
                Title: $data.ConfirmInfoStepText,
                Label: $data.ConfirmInfoStepText," class="taskGuide-popupInfoConfirmButton"></button>
            </div>
            <div data-dyn-bind="visible: $data.RailsSwitchAckVisible" class="taskGuide-popupInfoConfirm">
                <button data-dyn-role="Button" data-dyn-bind="
                Click: $data.onContinueTaskGuideClicked,
                Title: $label('TaskGuidesStep_RailsSwitchAckButton'),
                Label:$label('TaskGuidesStep_RailsSwitchAckButton')," class="taskGuide-popupInfoConfirmButton"></button>
            </div>
        </div>

        <div data-dyn-bind="" class="taskGuide-popupDetails">
            <button class="taskGuide-popupDetailsButton" data-dyn-role="Button" data-dyn-bind="
                ButtonDisplay: $dyn.ui.ButtonDisplay.textWithImageLeft,
                ImageType: 'Symbol',
                ImageName: $data.DetailsButtonSymbol,
                Click: $data.ToggleDetails,
                Title: $data.DetailsButtonTitle,
                Label: $data.DetailsButtonTitle"></button>

            <button class="taskGuide-popupDetailsNoteImage" data-dyn-role="Button" data-dyn-bind="
                    Visible: $dyn.computed(function(){ return $dyn.value($data.Note) != ''}),
                    ImageName: 'Note',
                    ImageType: 'Symbol',
                    Click: $data.ToggleDetails,
                    Title: $data.DetailsButtonTitle"></button>

            <div data-dyn-bind="visible: $data.DetailsGroupVisible">
                <div data-dyn-bind="visible: $data.ExampleGroupVisible">
                    <span data-dyn-role="Label" data-dyn-bind="Text: $label('TaskGuidesStep_ExampleLabel')" class="taskGuide-popupLabel taskGuide-popupSpan"></span>
                    <span data-dyn-role="Label" data-dyn-bind="Text: $data.Example" class="taskGuide-popupSpan"></span>
                </div>
                <div data-dyn-bind="visible: $data.NoteGroupVisible">
                    <span data-dyn-role="Label" data-dyn-bind="Text: $label('TaskGuidesStep_NoteLabel')" class="taskGuide-popupLabel taskGuide-popupSpan"></span>
                    <span data-dyn-role="Label" data-dyn-bind="Text: $data.Note" class="taskGuide-popupSpan"></span>
                </div>
                <div data-dyn-bind="" class="taskGuide-popupDetailsFooter">
                    <a data-dyn-role="AnchorButton" class="taskGuide-BackButton" data-dyn-bind="
                        Visible: $data.BackButtonVisible,
                        Click: $data.SkipBackGuidedStep,
                        Title: $label('TaskGuidesStep_BackStep'),
                        Label: $label('TaskGuidesStep_BackStep')">
                    </a>
                    <a data-dyn-role="AnchorButton" class="taskGuide-NextButton" data-dyn-bind="
                        Visible: $data.NextButtonVisible,
                        Click: $data.SkipGuidedStep,
                        Title: $label('TaskGuidesStep_NextStep'),
                        Label: $label('TaskGuidesStep_NextStep')">
                    </a>
                </div>
            </div>
        </div>
    </div>
</div>

<div id="AppDesignerPane" data-dyn-role="Dialog" data-dyn-bind="
       Caption: $dyn.format($dyn.label('SysAppDesigner_PaneTitle'), $dyn.shell.ProductName),
       Width: $dyn.layout.Size.available ,
       Height: $dyn.layout.Size.available,
       IsInViewMode: true,
       disposeOnClose: false,
       RequestClose: $dyn.util.emptyfunction" data-dyn-context="new $dyn.ax.AppDesignerPane()">
    <div id="appdesigner_part" data-dyn-role="Part" data-dyn-bind="
        RunMode:'Local',
        Visible:true,
        Width: $dyn.layout.Size.available,
        Height: $dyn.layout.Size.available,
        ObjectName: 'SysAppDesignerPane',
        InitPartForm: $dyn.serverForm.serializers.InitPartForm.deserialize(),
        CreatePartForm: $dyn.serverForm.serializers.CreatePartForm.deserialize(), ">
    </div>
</div>

﻿<div id="HelpPane" data-dyn-role="Dialog" data-dyn-bind="
       Caption: $label('HelpPane_Title'),
       Width: $dyn.layout.Size.available ,
       Height: $dyn.layout.Size.available,
       IsInViewMode: true,
       disposeOnClose: false,
       RequestClose: $dyn.util.emptyfunction">
    <div id="helppane_content" data-dyn-role="Part" data-dyn-bind="
        RunMode:'Local',
        Visible:true,
        Width: $dyn.layout.Size.available,
        Height: $dyn.layout.Size.available,
        ObjectName: 'SysHelpPane',
        InitPartForm: $dyn.serverForm.serializers.InitPartForm.deserialize(),
        CreatePartForm: $dyn.serverForm.serializers.CreatePartForm.deserialize(), ">
    </div>
</div>
<div id="HelpContextTracker" style="display:none" data-dyn-bind=""></div>

﻿<div id="TracingPane" data-dyn-role="Dialog" data-dyn-bind="
  Caption: $label('Tracing_PaneTitle'),
  Width: $dyn.layout.Size.available,
  Height: $dyn.layout.Size.available,
  disposeOnClose: false,
  RequestClose: $data.RequestClose" data-dyn-context="new $dyn.ax._tracingPane()">
    <div id=" tracing_steps" data-dyn-role="Part" data-dyn-bind="
    RunMode:'Local',
    Visible:true,
    Width: $dyn.layout.Size.available,
    Height: $dyn.layout.Size.available,
    ObjectName: 'SysTracingPane',
    InitPartForm: $dyn.serverForm.serializers.InitPartForm.deserialize(),
    CreatePartForm: $dyn.serverForm.serializers.CreatePartForm.deserialize(),">
    </div>
</div>





</div>

<script type="text/javascript">

function makeVersion() {
  $dyn.version={fullVerString:'7.0.22356.2',buildType:'retail'};
  window.console && window.console.info('build: %s %s', $dyn.version.fullVerString, $dyn.version.buildType);
};
makeVersion();
$dyn.templateVersion = "spring-2022";
$dyn.boot.preStart = function () {

  var self = $dyn.boot;
  self.log && self.log('Boot: preStart');

  
};

$dyn.boot.init = function () {
  var self = $dyn.boot;
  self.log && self.log('Boot: init');
  
  $dyn.shell.buildThemeValue = '0';
      $dyn.serverForm.init();
    
};

$dyn.boot.postNavigate = function () {
  var self = $dyn.boot;
  self.log && self.log('Boot: postNavigate');
  
};


$dyn.boot.loadInitalForm = function () {
  var self = $dyn.boot;
  self.log && self.log('Boot: loadInitalForm');
  $dyn.shell.loadInitialForm();
};

  $dyn.boot.start();

</script>





</body>
</html>
