# Getting Started

1. Install Git, Node and NPM. These versions should work well:
   - Node v9.3+
   - NPM v4.6 (NPM v5 is sketchy, so consider a downgrade via `npm install -g npm@4`).
   - Git v2.14+
2. Install [PhoneGap](http://docs.phonegap.com/getting-started/1-install-phonegap/cli/)
   - `sudo npm install -g phonegap@latest`
   - Test that it works: `phonegap` should output usage instructions. 
3. Fork and Clone this repo 
   - Example: `git clone https://github.com/MikeA1/pedi-crisis.git`
   - (or just download the project files)
4. Restore packages
   - `node update`
5. Start debugging
   - `phonegap serve` should output something like _listening on 192.168.0.5:3000_
      - Debug in a browser by navigating to the above IP address
      - Debug on iOS and Android with the [PhoneGap Developer](http://docs.phonegap.com/getting-started/2-install-mobile-app/) mobile app, 
         - If a Windows user, you may need to open port 3000 in Windows Firewall.

# Build

### Browser
This should work after Getting Started is completed. No additional steps needed.

### Android
Follow [these steps](https://cordova.apache.org/docs/en/latest/guide/platforms/android/index.html#requirements-and-support):
1. Install the [Java Development Kit (JDK)](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) v8 or later.
2. Install [Android Studio](https://developer.android.com/studio/index.html).


### iOS


