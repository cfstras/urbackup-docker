## about

This is a simple image for using urbackup in a small debian environment. Note that it's not extensibly tested, because I am probably the only user.

## starting

     docker run -d --name urbackup -v /var/urbackup:/var/urbackup -p 55413-55415:55413-55415 -p 35623:35623 cfstras/urbackup

