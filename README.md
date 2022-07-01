# Multicraft Management Console (1.4)
Allows you to manage your Multicraft server with a text based GUI -  Official support sites: [Official Github Repo](https://github.com/fstltna/MultiManagementConsole) - [Official Forum](https://minecity.online/index.php/forum/management-console)

---

You will need to run cpan and install these modules:

- cpan -i UI::Dialog
- cpan -i Term::ReadKey
- cpan -i Term::ANSIScreen
- cpan -i POSIX
- cpan -i Number::Bytes::Human

Run "mcmc". If you need to change any settings after this, edit "~/.mcmcrc" and make the desired changes. This can be done within mcmc itself.

You also need to have my Multicraft Startup Script and Multicraft Backup Script installed.

I then suggest you add this directory (MultiManagementConsole) into your path, so that you can just run "git pull" to upgrade to the latest version of mcmc as updates come out.
