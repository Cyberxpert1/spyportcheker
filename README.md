Surveillance Script to Catch any TCP Traffic coming Through as SSH
Is Someone at the Backdoor?
You suspect that someone is trying to open SSH session into your workstation and decided to set up a surveillance script to catch any TCP traffic Coming Through as SSH.

POC
1. In order to catch Ssh Traffic you need to monitor port 22
2. since we are only testing locally, you need to change Interface option
3. you can test script by opening a terminal window and execute ssh localhost.
   (It probably won't succeed unless you have an SSH server running but it will generate SSH Traffic)
4. Analyze The dump file with wireshark and Also decrypt via tcpdump -r (pcap file)
