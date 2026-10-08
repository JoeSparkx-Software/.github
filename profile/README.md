# JoeSparkx Software

Practical software, tools, and utilities built with a focus on making awkward things easier.

JoeSparkx Software is home to small, focused projects built primarily in C#/.NET, with an emphasis on useful desktop tools, gaming utilities, and open-source community projects.

## Projects

### Windows XIV Authenticator
<p align="center">
  <img
    src="https://github.com/JoeSparkx-Software/WindowsXIV-Authenticator/blob/main/WindowsXIVAuthenticator/assets/JSSAuthenticatorpic.png?raw=true"
    alt="Windows XIV Authenticator"
    width="420"
  />
</p>
A lightweight native Windows authenticator built for use with XIVLauncher.

Features include:

- TOTP authentication code generation
- Direct OTP handoff to XIVLauncher
- Launch XIVLauncher and send a fresh OTP automatically
- QR code import from image files
- QR code import directly from the Windows clipboard
- Google Authenticator export support
- Secure local secret storage using Windows DPAPI
- Optional Windows Hello verification
- Built-in stable release update checking
- Installer and portable builds

**Repository:**  
https://github.com/JoeSparkx-Software/WindowsXIV-Authenticator

**Releases:**  
https://github.com/JoeSparkx-Software/WindowsXIV-Authenticator/releases

## Windows XIV Authenticator XL Provider

[![Windows XIV Authenticator XL Provider](https://github.com/JoeSparkx-Software/.github/blob/main/profile/otpprovider.png)](https://github.com/JoeSparkx-Software/WindowsXIVAuthenticator-XLProvider)

A small OTP provider DLL for XIVLauncher that lets it fetch one-time passwords from [Windows XIV Authenticator](https://github.com/JoeSparkx-Software/WindowsXIV-Authenticator).

I built my own authenticator integration as the first test case for the provider system and confirmed the full flow works end to end:

**XIVLauncher → Provider DLL → Windows XIV Authenticator → Windows Hello → OTP → Login**

The provider repo also includes a simple example implementation so anyone wanting to support another authenticator can fork it or copy the sample and wire in their own provider.

[Provider DLL](https://github.com/JoeSparkx-Software/WindowsXIVAuthenticator-XLProvider) · [Windows XIV Authenticator](https://github.com/JoeSparkx-Software/WindowsXIV-Authenticator/releases)

---

## Support

JoeSparkx Software projects are developed independently and made available free to use.

If you find them useful and want to support further development:

**Ko-fi:**  
https://ko-fi.com/joesparkx

Support is entirely optional and does not unlock features or functionality.

---

## Development

Projects are generally built around:

- C#
- .NET
- Windows
- WPF
- Open-source tooling
- GitHub

Where appropriate, source code is published openly so others can inspect, learn from, contribute to, or build on the work within the terms of each project's licence.

---

## Security

Security issues should be reported through the relevant project's GitHub repository where possible.

For Windows XIV Authenticator, no authenticator secrets, account credentials, telemetry, or usage data are sent to JoeSparkx Software.

---

## Community

You can also find related projects and resources through:

- GitHub — https://github.com/JoeSparkx-Software
- Ko-fi — https://ko-fi.com/joesparkx
- Discord - https://discord.gg/WCevxNTjCa

---

## Disclaimer

JoeSparkx Software is an independent project and is not affiliated with or endorsed by Square Enix, FINAL FANTASY XIV, XIVLauncher, or their respective developers.

Individual projects may include additional project-specific disclaimers, licences, and attribution requirements.
