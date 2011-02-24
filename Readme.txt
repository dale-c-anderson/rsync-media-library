Part I:

 Local machine = work computer (windows 7)
 remote machine = web server (windows 2003)

1) Clean up / groom local library - make it look proper; it's about to get duplicated to your remote server. 
2) run artistalbums-push.sh
3) Go to remote server, and clean up that library. Make it look proper. It's about to get duplicated to your local library.
4) run artistalbums-pull.sh ------ MONITOR CLOSELY to see that nothing is coming back that you didn't want. Ctrl+C the script as needed to re-groom both libraries, and restart the script.
5) Re-evaluate how your local library looks. 