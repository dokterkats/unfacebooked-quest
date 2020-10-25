<h1>sideloading</h1>
<p>There are 2 main methods to sideload. You can use adb or sidequest.</p>
<p>You need to have Developer mode enabled for both methods.</p>
<p>&nbsp;</p>
<h2><a id="user-content-enabling-developer-mode" class="anchor" href="https://github.com/dokterkats/unfacebooked-quest/tree/main/sideloading#enabling-developer-mode" aria-hidden="true"></a>enabling Developer mode</h2>
<p>There's no toggle for this from within the headset. You can only do this from the Oculus app for iPhone, iPad or Android</p>
<p><br />step 1: Select &ldquo;Settings&rdquo; from the app, click on your headset (make sure to turn on your headset), and select &ldquo;More Settings.&rdquo;<br />step 2: Select &ldquo;Developer Mode.&rdquo;<br />step 3: Toggle the switch on.<br /><br />Oculus began requiring people to sign up for their developer program to turn on developer mode. This process is free and easy.</p>
<h3><a id="user-content-creating-an-organisationstep-1-create-organisation-at-dashboardoculuscomstep-2-youll-be-asked-to-accept-the-developer-agreement-agree-to-this" class="anchor" href="https://github.com/dokterkats/unfacebooked-quest/tree/main/sideloading#creating-an-organisationstep-1-create-organisation-at-dashboardoculuscomstep-2-youll-be-asked-to-accept-the-developer-agreement-agree-to-this" aria-hidden="true"></a>creating an organisation:</h3>
<p>Step 1: Create Organisation at dashboard.oculus.com<br />Step 2: You'll be asked to accept the developer agreement. Agree to this.</p>
<p>&nbsp;</p>
<h2><a id="user-content-sidequest" class="anchor" href="https://github.com/dokterkats/unfacebooked-quest/tree/main/sideloading#sidequest" aria-hidden="true"></a>sidequest:</h2>
<p><a href="https://sidequestvr.com/setup-howto" rel="nofollow">https://sidequestvr.com/setup-howto</a></p>
<p>&nbsp;</p>
<h2><a id="user-content-adb-android-platform-tools" class="anchor" href="https://github.com/dokterkats/unfacebooked-quest/tree/main/sideloading#adb-android-platform-tools" aria-hidden="true"></a>adb android platform tools</h2>
<h3><a id="user-content-windows" class="anchor" href="https://github.com/dokterkats/unfacebooked-quest/tree/main/sideloading#windows" aria-hidden="true"></a>Windows:</h3>
<p>step 1: download the android platform tools on&nbsp;<a href="https://developer.android.com/studio/releases/platform-tools" rel="nofollow">https://developer.android.com/studio/releases/platform-tools</a><br />step 2: open the cmd<br />step 3: cd to your platform tools folder. For example: C:\Users\user1\Downloads\platform-tools<br />step 4: enter adb devices, this will automaticly start daemon</p>
<p>(if no devices show up try running the command again or check if theres an pop up in your headset asking to allow usb debugging, allow usb debugging)</p>
<p>step 5: enter apk install app.apk (make sure to put the apk files in the platform-tools folder, change "app" to whatever the name of the app you want to install is)</p>
<p>&nbsp;</p>
