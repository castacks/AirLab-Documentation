Flashing and Initial setup
==========================

Step 1: Xavier Flashing
-----------------------
  1.1 Bitbucket SSH

  * Setup the Bitbucket ssh key on your own computer.

  * https://support.atlassian.com/bitbucket-cloud/docs/set-up-an-ssh-key/.

  1.2 Clone the repo
    
  * https://bitbucket.org/castacks/mmpug_xavier_flashing/src. 

    * Clone and run everything on your own computer (master branch).

  * Run .. highlight: python

        :code:`"some" "highlighted code"`

  * Put Xavier to recovery mode .

    * Jetson should be powered off.
      #. Press and hold down the Force Recovery button. (middle one)

      #. Press and hold down the Power button.
      
      #. Release both buttons.

   * Connect Xavier with your own computer through a usb-usbc line. Usbc on xavier, usb on your own computer.
  
  * Follow the ReadMe instructions till Flash Sections.

    * Make sure Xavier is connected to the Screen, equipped with a mouse and a keyboard.

    * Don’t unplug the usb-usbc line until the whole system is completely booted up (including setup username, pass words and etc) .
