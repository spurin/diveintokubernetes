# Dive Into Kubernetes - Containers, Docker and Kubernetes - GCP Cloudshell - Tutorial

![DiveInto](https://raw.githubusercontent.com/spurin/diveintokubernetes/cloudshell/DiveIntoKubernetes.jpeg)

This tutorial provides you with a fully working Kubernetes lab, accessible in your browser 🚀

Execute the following command to setup the lab environment.

For convenience you can send this to the terminal using the convenient 'Copy to Cloud Shell' icon on the top right of the text box

```bash
bin/docker-compose up -d
```

When this completes, you'll see text similar to the following -

```terminal
[+] Running 3/3
 ✔ Network kubernetes.cloudshell.diveinto.io                             Created                                                                      0.1s 
 ✔ Container control-plane-dive-into-kubernetes-introduction-cloudshell  St...                                                                        5.7s 
 ✔ Container portal-dive-into-kubernetes-introduction-cloudshell         Started                                                                      1.1s 
```

To access the Portal, click the Web Preview Icon, if you cant find it, click -> <walkthrough-web-preview-icon>here</walkthrough-web-preview-icon> for a walkthrough on where to find it.  

Select 'Preview on Port 8080' and you're good to go!  

When accessing terminals, the default credentials are root/root

Should you require, you can factory reset the environment with the following, your terminals will disconnect and reconnect -

```bash
bin/docker-compose down -v; bin/docker-compose up
```
