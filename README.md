# AES67 Player

The AES67 Player application is an Android application that can be used to play to your AES67 streams.

The application is currently in testing phase, it's limited to 60 seconds of playback, 
and it's distributed via the Google Play Store at: [AES67 Player - Trial](https://play.google.com/store/apps/details?id=com.bondagit.aes67player)

# Introduction

Play your AES67 audio streams directly on your Android devices for testing, previewing or just for fun by using the AES67 Player and the AES67 Linux Daemon.

The AES67 Linux Daemon is an open source Linux application and you can find it at: [AES67 Linux Daemon](https://github.com/bondagit/aes67-linux-daemon)

The diagram below shows the various components and how they interact:
![Screenshot 2024-06-15 at 15 36 48](https://github.com/user-attachments/assets/8e2a8c58-c811-48c7-8954-4596331d862f)


# Setup instruction

To use the Player follow these instructions:

1. Install and configure the AES67 Linux daemon v2.0 or above on a Linux host and attach it to your AES67 LAN, see [How to build and setup the daemon](https://github.com/bondagit/aes67-linux-daemon?tab=readme-ov-file#how-to-build-and-setup-the-daemon).
2. Using the AES67 Linux daemon WebUI, in the Config tab, check the daemon version and enable the Streamer feature. See picture below:   <img width="790" alt="Daemon config" src="https://github.com/user-attachments/assets/9d2a6ae9-ab7d-4c2e-83dd-a323366465ac">.
4. Attach one or more AES67 or Dante Sources to your LAN. See [Compatible Device](https://github.com/bondagit/aes67-linux-daemon/blob/master/DEVICES.md)
5. Using the AES67 Linux daemon WebUI, in the Sinks tab, create one of more Sinks specifying the AES67 Sources discovered by the daemon. See picture below: <img width="597" alt="Daemon Sinks list" src="https://github.com/user-attachments/assets/8b8b5832-96a0-437c-b3df-ff233234f881">.
6. Open the AES67 Player application and enter the URL of the AES67 Linux daemon WebUI.
7. When the daemon appears in the daemon's list click on the go icon on the right side to connect to it. See picture below: <img width="342" alt="Player Daemons list" src="https://github.com/user-attachments/assets/ee2bdb93-cb5f-4c23-9126-b0bf1d87a784">

8. On the Sinks page start or stop a Sink playback by using the play icon on the right. See picture below: <img width="340" alt="Player Sinks list" src="https://github.com/user-attachments/assets/ae816d6b-2d00-49e1-8c77-98df1e140d4e">

9. Expand a Sink info by clicking on the expand icon on the left. See picture below: <img width="344" alt="Player Sink expanded" src="https://github.com/user-attachments/assets/de0d2cb4-b1d9-47a7-a4c8-02ff32c55797">
