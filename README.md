# Pwnleo

A modern APT package manager frontend

# Info

Sileo focuses on speed, features, and a modern feel. It is made with love by people from all over the world!

# Compile

1. Clone this repository
    ```sh
    git clone https://github.com/BananeRapeuse/Pwnleo
    ```
2. Set the `DEVELOPMENT_TEAM` Build Setting
    
    There are multiple ways to do this, for example:
    
    * Using Xcode Custom Paths
        * Go to Xcode > Preferences > Locations > Custom Paths
        * Add an entry with `Name` as `DEVELOPMENT_TEAM`, `Display Name` as `Development Team`, and `Path` as your Apple Developer Team ID
    * Using Xcode Build Settings
        * Set the `Development Team` Build Setting
        * Remember to never commit this change
        
3. Apply our git hooks by running: `git config core.hooksPath .githooks`
4. Open `Sileo.xcodeproj` and have at it!
