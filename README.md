# lic_serv_agent

1. Use CentOS 7 (RHEL7-based) with kernel 3.10 or AlmaLinux 8 (RHEL8-based) with kernel 4.18.
2. Compiler GCC must be installed (exists at CentOS 7 Minimal install / AlmaLinux 8 Minimal install).
3. Use locale=en_US.UTF-8.
4. Put the file "lic_serv_agent.zip" (or "lic_serv_agent_alma8.zip") to /opt (or another dir).
5. "cd /opt" + "unzip lic_serv_agent.zip".
6. "cd /opt/lic_serv_agent".
7. "chmod +x lic_serv_agent_0.exe".
8. For run "./lic_serv_agent_0.exe".
9. Fill the configuration file "/opt/lic_serv_agent/lic_serv_agent.cfg".
10. For stop "./lic_serv_agent_0.exe stop".
11. For restart "./lic_serv_agent_0.exe restart".
12. For reload configuration "./lic_serv_agent_0.exe reload_cfg".
13. For use systemd "./lic_serv_agent_0.exe use_systemd" and follow instructions.
