# do_ex2_SamynMathias

How to use:

- vagrant up (This will make all the devices and provision them)
- go to localhost:8080
- (to see the HAProxy stats, go to: localhost:8080/haproxy?stats)

How to do the zero downtime rolling deployment

- change something in templates/index.html.j2
- vagrant ssh mgr
- ansible-playbook rolling-deployment.yml
