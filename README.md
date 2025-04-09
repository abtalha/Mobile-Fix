## Without Pc How Unbrick Mobile

 * Install Buggjeager :- https://play.google.com/store/apps/details?id=eu.sisik.hackendebug
 * Download available TWRP or custom recovery
 * Download fastboot Rom

   * Now Unzip FastBoot Rom And Copy All .img File In Internal Storage
* Now Connect Brick Mobile with USB Cable another Mobile
  * Open Buggjeager Apps
     ```
        fastboot devices
     ```
     * Use Cmd Multiple times And Plug Unplug If Not Show FastBoot Code
   
  * Now Flash All .img
    ```
       fastboot flash boot [BooT File Location]
    ```
    ```
      fastboot flash catch /sdcard/catch.img
    ```

  * After Complete Flash all file
  * Brick Mobile Volume up+Power button press And Go Stock Recovery Mode
  * Again in mobile Boot in fastboot Mode
 
     * Now Flash Recovery Twrp
         ```
           fastboot flash recovery recovery.img
         ```
         
