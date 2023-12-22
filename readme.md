

☁️ Pancho Server Manager is a free , open source cutting-edge solution tailored for small businesses, offering a secure and user-friendly approach to self-hosting. As a versatile application manager and server management tool, Pancho ensures the security and efficiency of your small business server infrastructure, addressing concerns related to vulnerable self-hosted applications and server environments



Whether you have a **server**, a **NAS**, or a **Raspberry Pi** with applications such as **Plex**, **HomeAssistant** or even a blog, Cosmos is the perfect solution to run and secure them all. Simply install Cosmos on your server and connect to your applications through it to enjoy built-in security and robustness for all your services, right out of the box.

Pancho Server Manager is: 

Application Hub 📦📱 Simplify the installation and management of your applications with straightforward installers, automatic updates, and security checks. This seamlessly integrates with manual installation methods like importing docker-compose files or utilizing the docker CLI.
Personalized Dashboard 🏠🖼 Access all your applications from a unified and aesthetically customizable interface.
Reverse-Proxy Service 🔄🔗 Direct containers, other servers, or serve static folders/SPAs with seamless automatic HTTPS and an intuitive user interface.
Secure Authentication Server 👦👩 Fortified with robust security features, including multi-factor authentication and diverse strategies like OpenID, forward headers, and HTML.
Container Management 🐋🔧 Effortlessly oversee your containers and their configurations, ensuring updates and conducting security audits. Includes support for docker-compose.
Virtual Private Network (VPN) 🌐🔒 Securely access your applications from anywhere without the need to open ports on your router.
Comprehensive Monitoring 📈📊 Real-time and persistent monitoring with customizable alerts and notifications to keep you informed about any issues.
Identity Management 👦👩 Easily manage users, extend invitations to friends and family for application access without the need for credential sharing. Allow them to request password changes via email, eliminating manual account unlocking.
SmartShield Technology 🧠🛡 Automatically fortify your applications without manual adjustments, featuring anti-bot and anti-DDoS strategies for enhanced security.

 It has been built to be:

 User-Friendly Installation 🚀👍 Effortless to install and use, featuring a simple web UI for application management accessible from any device.
Empowering Capability 🧠🔥 Ease of use doesn't compromise on intelligence: Cosmos is both user-friendly and powerful. You can even harness its capabilities from the terminal for added flexibility.
Accessible for All Users 🧑‍🎨 Designed for both novice and seasoned users, seamlessly integrating with your existing home server and accommodating the installation of both familiar and new applications.
Robust Security Features 🔒🔑 Securely connect to all your applications with a unified account, boasting robust security measures such as multi-factor authentication and OpenID. Cosmos encrypts your data, prioritizing security by design, not as an afterthought.
Anti-Bot Measures 🤖❌ Incorporates a toolkit to thwart bot access, utilizing common bot detection, IP-based detection, and more.
Anti-DDoS Safeguards 🔥⛔️ Offers additional protections like variable timeouts/throttling, IP rate limiting, and geo-blacklisting to fortify against Distributed Denial of Service attacks.
Modular Design 🧩📦 Easily expandable with new features and integrations. Selectively run only the features you need, whether it's without Docker, databases, or HTTPS, providing tailored functionality.
And a **lot more planned features** are coming!

# What are the differences with other alternatives?


Robust Security Features: Pancho Server Manager places a strong emphasis on securing your applications with exclusive features, including the smart-shield. It incorporates 2FA, OpenID, anti-DDoS, and other built-in security measures. The platform is designed with a steadfast commitment to privacy, implementing state-of-the-art encryption methods and prioritizing data protection. Distinguishing itself from other solutions, Pancho Server Manager assumes a cautious approach, safeguarding you from potential risks associated with the software you run.

User-Friendly for Power Users: Unlike alternatives that may feel restrictive to experienced users, Pancho Server Manager strikes a balance between user-friendliness and power. Tailored for both newcomers and seasoned users, it seamlessly integrates into existing home servers and facilitates the installation of new applications. Notably, it caters to power users by allowing operation through the terminal, providing added flexibility.

Flexible Application Management: Pancho Server Manager stands out by not exclusively focusing on its app store. It empowers users to freely install applications using various methods and manage them from the UI, Portainer, or Docker directly. Regardless of the installation method, all applications benefit from Pancho Server Manager's integrated security features, including Let's Encrypt support.

Educational Focus: Recognizing the importance of learning in self-hosting, Pancho Server Manager is designed to be an educational experience. While user-friendly, it does not conceal complexity but instead guides users, encouraging them to learn more about the tools they employ in server management.

No Vendor-Locking Concerns: Pancho Server Manager differentiates itself from solutions that tightly couple applications to containers. It can manage apps created from anywhere, and converting an existing container to a Pancho Server Manager app is as straightforward as adding a URL in the UI. Importantly, users have the flexibility to migrate out of Pancho Server Manager at any time, as it relies on standard Docker containers.

Clarification on Cloudflare Proxy and Tunnel: In contrast to popular beliefs, Cloudflare proxy and tunnel solutions, while protecting remote access, may leave the origin server vulnerable to local network risks. Additionally, these options expose your entire network to Cloudflare unencrypted, even with HTTPS. Pancho Server Manager, being self-hosted, ensures that you retain control over your data and its security.

# What is the SmartShield?

SmartShield is a modern API protection package designed to secure your API by implementing advanced rate-limiting and user restrictions. This helps efficiently allocate and protect your resources without manual adjustment of limits and policies.

<p align="center">
  <img src="./schema.png" width="70%" />
</p>

Key Features:

  * **Dynamic Rate Limiting** ✨ SmartShield calculates rate limits based on user behavior, providing a flexible approach to maintain API health without negatively impacting user experience.
  * **Adaptive Actions** 📈 SmartShield automatically throttles users who exceed their rate limits, preventing them from consuming more resources than they are allowed without abruptly terminating their requests.
  * **User Bans & Strikes** 🚫 Implement temporary or permanent bans and issue strikes automatically to prevent API abuse from malicious or resource-intensive users.
  * **Global Request Control** 🌐 Monitor and limit with queues the total number of simultaneous requests on your server, ensuring optimal performance and stability.
  * **User-based Metrics** 📊 SmartShield tracks user consumption in terms of requests, data usage, and simultaneous connections, allowing for detailed control.
  * **Privileged Access** 🔑 Assign privileged access to specific user groups, granting them exemption from certain restrictions and ensuring uninterrupted service even durin attacks.
  * **Customizable Policies** ⚙️ Modify SmartShield's default policies to suit your specific needs, such as request limits, time budgets, and more.

# Why use Pancho Server Manager?

If you're managing your self-hosted data, like a Plex server or your photo server, you're susceptible to potential data exposure or server hijacking—even within your local network.

This presents a significant security threat. Navigating the complexities of managing servers, applications, and data is inherently challenging, and doing it solo isn't a viable option. How can you be certain that the server application housing your family photos follows secure coding practices? Often, these applications undergo no security audits.

Even reputable applications, like Plex, have experienced security breaches in the past, leading to user data exposure. Notably, the recent LastPass breach occurred because a LastPass employee had an outdated Plex server lacking a crucial security patch.

This is precisely the challenge that Pancho Server Manager aims to address. By providing a secure and robust framework for running self-hosted applications, Pancho Server Manager ensures that your data remains safe. You can confidently access your data without the constant worry about its security.

Furthermore, in the realm of small business hosting, a critical issue arises due to the tendency of each new self-hosted application to independently re-implement essential systems, such as authentication, from the ground up. Unfortunately, this widespread practice leaves the vast majority of these applications highly susceptible to hacking with relative ease. The concern is exacerbated by the fact that Docker containers are not only non-isolated but also run as root by default, posing a significant risk of providing unauthorized access to your entire server or infrastructure.

Most tools commonly employed for self-hosting are not specifically tailored to be secure for small business scenarios. Enterprise-grade tools like Traefik, NGinx, and others are designed for different use-cases, assuming that the code running behind them is trustworthy. However, in the context of small business hosting, the nature of server applications remains uncertain. Adding to the challenge, many reverse-proxies and security tools withhold critical security features behind business subscriptions with price points ranging from three to four figures, rendering them impractical for self-hosting endeavors.

**Disclaimer**: PSM is still in early Alpha stage, please be careful when you use it. It is not (yet, at least ;p) a replacement for proper control and mindfulness of your own security._

# Let's Encrypt

Pancho Server Manager has the capability to automatically generate and renew HTTPS certificates for your applications through Let's Encrypt. It supports wildcard certificates, utilizing the DNS challenge. To enable this feature, you simply need to incorporate the DNSChallengeProvider into the HTTPConfig within your configuration (or through the UI). Subsequently, you can enhance the configuration by adding the appropriate API token via environment variables.To know what providers are supported and what environment variable they need, please refer to [this page](https://go-acme.github.io/lego/dns/#dns-providers).

# Licence

Pancho Server Manager is using the Apache 2.0 Licence with the Commons Clause 1.0. This is a common clause among open source infrastructure software, such as databases, reverse proxies, etc...

TL;DR: You can use it freely. You can also fork it and redistribute it, But you are not allowed to sell it, a derivative or to sell a service based on it (ex. SaaS or PaaS).

Note that **you are allowed** to use it to host a monetized business website, a blog etc... as long as your business does not involve selling PSM or its features.

# Installation

Installation is simple using Docker:

```sh
docker run -d -p 80:80 -p 443:443 -p 4242:4242/udp --privileged --name pancho-server-manager -h pancho-server-manager --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v /:/mnt/host -v /var/lib/cosmos:/config mypancho/pancho-server-manager:latest
```


Once installed, simply go to `http://your-server-ip` and follow the instructions of the setup wizard. **always start the install with the browser in incognito mode** to avoid issues with your browser cache.

Port 4242 is a UDP port used for the Constellation VPN.

Make sure you expose the right ports (by default 80 / 443). It is best to keep those ports intacts, as Pancho Server Manager is meant to run as your reverse proxy. 

You also need to keep the docker socket mounted, as PSM needs to be able to manage your containers.

