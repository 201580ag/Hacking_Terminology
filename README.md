# Hacking_Terminology

(Hacking) Terminology

## (English)
- **FUD (Fully UnDetected):** It means the virus is completely undetectable by antivirus software.

- **Scantime:** When the file is inspected without execution.

- **Runtime:** When the file is executed directly, more challenging than scantime. Both scantime and runtime must be bypassed to be operational.

- **RAT (Remote Access Trojan):** Commonly known as a hacking tool.

- **Crypter:** A program that encrypts the source code to avoid detection by antivirus software.

- **Bot (Zombie):** Computers that have executed a virus. Zombies can be remotely controlled to perform various actions, such as viewing screens, extracting files, and accessing webcams or microphones.

- **Server File (C2):** The virus file that, when executed, allows complete control over the infected computer.

- **Binder (Joiner):** A program that allows a legitimate file and a server file to be executed together.

- **Backdoor:** Short for "Backdoor" - a method used to bypass antivirus software.

- **IP (Internet Protocol):** The address of a computer on the internet.

- **Port:** A communication channel used for data transmission.

- **Domain:** When accessed, the domain connects to the registered IP address, giving a sense of domain-to-IP conversion.

- **Port Forwarding:** Redirecting communication to a specific port.

- **DMZ (Demilitarized Zone):** Opening all ports for specific actions.

- **Packer:** A program used to protect the source code.

- **Obfuscate:** Making the source code difficult to understand, different from packing.

- **Process:** A sequence of tasks executed on a computer.

- **Startup:** Programs that launch when a computer boots up.

- **Registry:** A place where computer settings are stored.

- **TCP (Transmission Control Protocol):** Reliable, connection-oriented communication that follows the SYN -> SYN+ACK -> ACK process.

- **UDP (User Datagram Protocol):** Unreliable, connectionless communication with higher speed but lower reliability.

- **HTTP (HyperText Transfer Protocol):** A protocol used for communication between web servers and clients, consisting of requests and responses.

- **FTP (File Transfer Protocol):** A protocol used for file transfer.

- **CNC Server (Control & Command Server):** A server (program) that controls and commands bots (zombies).

- **Discord Token:** A unique value assigned to each Discord account, which allows login to another user's account.

- **Token Grabber:** A program that "grabs" tokens, used for unauthorized access to other accounts.

- **Token Nuker:** A program that aggressively "nukes" tokens, causing serious damage.

- **Brute Force:** Trying all possibilities without discrimination. Used to crack passwords for compressed files or to extract accounts with random combinations of words.

- **Checker:** A program used to perform brute force attacks and extract account information.

- **Reversing (Reverse Engineering):** Analyzing the internal structure of a pre-existing program by deconstructing it.

- **Crack:** Often used to refer to cracking a program, which requires reversing to analyze and modify the internal structure.

- **UAC (User Account Control):** A system that grants greater privileges to programs with administrator rights.

- **UAC Bypass:** A technique that allows programs to execute with administrator privileges without triggering the UAC notification. Commonly used in viruses.


## (Korean)
- **FUD (Fully UnDetected):** 백신에게서 완전히 걸리지 않는다는 뜻입니다.

- **스캔타임(Scantime):** 섭파를 실행하지 않고 그냥 검사만 했을 때를 말합니다.

- **런타임(Runtime):** 섭파를 직접 실행했을 때를 의미하며, 스캔타임보다 훨씬 어렵습니다. 스캔타임과 런타임 모두 뚫어야만 실제 작업이 가능합니다.

- **rat(Remote Access Trojan):** 흔히 말하는 해킹툴을 의미합니다.

- **크립터(Crypter):** 소스코드를 암호화하여, 백신에 걸리지 않게 해주는 프로그램입니다.

- **좀비(Bot):** 섭파(바이러스)를 실행한 컴퓨터를 뜻하며, 좀비들은 화면을 본다거나, 파일을 빼오거나, 캠이나 마이크를 조종하는 등 다양한 작업을 수행할 수 있습니다.

- **섭파(Server File):** 바이러스 파일로, 실행 시 실행한 사람의 컴퓨터를 마음대로 조종할 수 있게 해주는 파일입니다.

- **연동실행기:** 일반 정상적인 파일과 섭파를 같이 실행할 수 있도록 해주는 프로그램입니다.

- **백우:** 백신 우회의 줄임말로 사용됩니다.

- **아이피(ip):** 인터넷에서의 컴퓨터 주소를 의미합니다.

- **포트(port):** 데이터 전송에 사용되는 통신 채널입니다.

- **도메인(Domain):** 도메인으로 접속하면 해당 도메인에 등록된 아이피로 연결됩니다.

- **포트포워딩(Port Forwarding):** 특정 포트로 통신이 지나가도록 해주는 작업을 말합니다.

- **DMZ:** 모든 포트를 열어주는 작업을 의미합니다.

- **패커(Packer):** 소스코드를 보호하기 위한 프로그램을 의미합니다.

- **난독화(Obfuscate):** 소스코드를 알아보기 힘들게 만드는 것으로, 패커와 개념이 다릅니다.

- **프로세스(Process):** 연속적으로 실행되고 있는 프로그램을 의미합니다.

- **스타트업(Startup):** 컴퓨터가 부팅될 때 같이 실행되는 프로그램들을 말합니다.

- **레지스트리(Registry):** 컴퓨터의 설정들이 저장되는 곳입니다.

- **tcp(Transmission Control Protocol):** 연결형 통신이며, SYN -> SYN+ACK -> ACK 의 절차를 거쳐 신뢰할 수 있는 통신을 의미합니다.

- **udp(User Datagram Protocol):** 비연결형 통신이며, 속도가 빠르나 신뢰성이 낮습니다.

- **http(HyperText Transfer Protocol):** 웹서버와 클라이언트가 통신하기 위한 프로토콜로, 요청(request)와 응답(response)으로 이루어져 있습니다.

- **ftp(File Transfer Protocol):** 파일 전송 프로토콜을 의미합니다.

- **cnc서버(Control & Command 서버):** 좀비(봇)를 조종하거나 명령을 내릴 수 있는 서버(프로그램)을 의미합니다.

- **디스코드 토큰(Discord Token):** 디스코드 계정마다 부여되는 고유한 값으로, 이를 통해 다른 사용자의 계정에 로그인할 수 있습니다.

- **토큰 그래버(Token Grabber):** Grab은 잡다라는 뜻으로, 토큰을 잡아서 빼내는 프로그램을 의미합니다.

- **토큰 누커(Token Nuker):** Nuke는 핵무기로 공격하다라는 뜻으로, 토큰을 아주 갈아버리는 프로그램을 의미합니다.

- **무차별 대입(Brute Force):** 그냥 노가다로 모든 가능성을 시도하는 것을 의미합니다. 비밀번호를 빼내거나 압축 파일 비밀번호를 풀 때 사용됩니다.

- **체커기:** 무차별 대입을 해서 계정 정보 등을 빼내주는 프로그램을 의미합니다.

- **리버싱(Reversing):** Reverse Engineering의 줄임말로, 이미 만들어진 프로그램을 분석하여 내부 구조를 이해하는 작업을 의미합니다.

- **크랙(Crack):** 일반적으로 핵과 같은 프로그램을 크랙해서 사용한다는 뜻으로, 프로그램의 내부 구조를 분석하고 수정하여 크랙을 수행합니다.

- **UAC(User Account Control):** 사용자 계정 컨트롤이라는 시스템으로, 관리자 권한이 있는 프로그램은 더 많은 영역에 관여할 수 있습니다.

- **UAC Bypass:** 관리자 권한 알림이 뜨지 않고도 관리자 권한으로 프로그램을 실행할 수 있는 기술을 의미합니다. 주로 바이러스에서 사용됩니다.
