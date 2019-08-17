# SSH Connection Manager

## A free and open-source connection manager

- 멀티 SSH 세션을 관리하는 프로그램
- ssh client 로 잘 알려진  PAC (Perl Auto Connector) Manager 를 포크하여 개작한 프로그램
- 하모니카 리눅스에서 사용할 수 있도록 재 패키징

### Features

- Simple GUI to manage/launch connections to remote machines
- Scripting possibilities, 'ala' SecureCRT
- Configurable pre or post connection local commands execution
- Configurable list of macros (commands) to execute locally when connected or to send to connected client
- Configurable list of conditional executions on connected machine via 'Expect':
  - forget about SSH certificates
  - chain multiple SSH connections
  - automate tunnels creation
  - with line-send delay capabilities
- [KeePassX](https://www.keepassx.org/) integration
- Ability to connect to machines through a Proxy server
- Cluster connections
- Tabbed/Windowed terminals
- Wake On LAN capabilities
- Local and global variables, eg.: write down a password once, use it ANY where, centralizing its modification for faster changes! use them for:
  - password vault
  - reusing connection strings
- Seamless Gnome/Gtk integration
- Tray icon for 'right button' quick launching of managed connections. Screenshots and statistics.
- DEB, RPM and .TAR.GZ packages available

### 하모니카 에서 설치

- HamoniKR

  ````
  $ wget https://packagecloud.io/install/repositories/asbru-cm/asbru-cm/script.deb.sh
  $ chmod +x script.deb.sh
  $ sudo os=ubuntu dist=bionic ./script.deb.sh 
  $ sudo apt-get install asbru-cm
  ````

### License

This Program is licensed under the GNU General Public License version 3 <http://www.gnu.org/licenses/gpl-3.0.html>.  
