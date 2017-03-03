Sample Ansible playbooks
============================================

Here are a few sample playbooks.  These assume that you already have an
Ansible setup going.  You can then drop the files of the example
directly into your setup.

* [mailserver/](mailserver/) sets up a mail server with Dovecot, Postfix,
   the SSL certificates you provide yourself, SPF, and the DKIM
   certificates that you create.  See `vars/mail.yml` inside this
   directory for instructions on domains, users, host names,
   SSL and DKIM.
* [jenkins/](jenkins/) sets up a Jenkins server with a number of plugins.
* [zfsupdates/](zfsupdates/) aids you in keeping ZFS up to date on your
   Fedora system which boots from ZFS.
* [distupgrade/](distupgrade/) upgrades your Fedora machine to a newer
  release, taking appropriate recovery precautions.
* [prosodyxmpp/](prosodyxmpp/) sets up Prosody XMPP on your Fedora
  box, with up-to-date XEPS for use with modern XMPP clients.
* [qubeskde/](qubeskde/) sets up KDE on any Qubes OS dom0, since Qubes OS
  decided to stop shipping KDE in the dom0.

See `README.md` files inside each directory, when they exist.

Licensing
---------

Everything under this repository is distributed under the GNU GPL v2
or later.
