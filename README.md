// make sure device is MIUI device, else an 
// exception will be thrown at initialization
Autostart autostart = new Autostart(applicationContext);

State state = autostart.getAutoStartState();

Autostart autostart = new Autostart(applicationContext);

// get the list of packages which are 
// white-listed by system by default
        
String[] packagesWhiteListed = autostart.defaultWhiteListedPackages();repositories {
    maven { url 'https://jitpack.io' }
}android {
    dependenciesInfo {
        includeInApk = false
        includeInBundle = false
    }
}
-runauto
