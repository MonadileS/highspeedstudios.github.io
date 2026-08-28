# Privacy Policy

**Custom Tunnel — AIO Tunnel VPN**
Developer: HighSpeedStudios
Contact: moodesigner.99@gmail.com
Last updated: 28 August 2026

HighSpeedStudios develops **Custom Tunnel — AIO Tunnel VPN** (package `com.customtunnel.aiotunnelvpn`) as a free, ad-supported Android application. It is provided at no cost and is intended to be used as is.

This page explains how we collect, use, and disclose information when you use our app. It applies to the app published under our developer account that relies on the same permissions and features described below.

If you choose to use our app, you agree to the collection and use of information in accordance with this policy. Information is used only to provide and improve the app. We do not use or share your information with anyone except as described here.

## Information Collection and Use

To work at all, the app asks you to enter connection details yourself: server addresses, ports, and in some cases account credentials or configuration files. These details are stored on your device and encrypted at rest using AES encryption. If you use the optional subscription/configuration import feature, the source URL and configuration content are fetched from the URL you supply.

We do not operate an account system and we do not ask you to register. The app also includes third-party services that may collect information used to identify you, as described in the Advertising section.

Links to the privacy policies of the third-party service providers used by our app:

- [Google Play Services](https://www.google.com/policies/privacy/)
- [Google AdMob](https://support.google.com/admob/answer/6128543)

## VPN and Tunneling

The app uses the Android VPN service to route your device traffic through servers or proxies that you configure yourself. The app is a client only: we do not operate those servers and we do not decide where your traffic goes.

We do not intercept, read, store, or sell the content of your traffic, and we do not keep browsing history. Traffic flows only between your device and the server you choose. The operator of that server, and your internet provider, may still see traffic according to their own policies.

While a tunnel is active, Android runs an active VPN service. Its status notification is shown when notification permission is allowed; otherwise, the service may appear only under Active apps or Task Manager. The app offers additional on-device features: choosing which installed apps use the tunnel (requires reading the list of installed apps via `QUERY_ALL_PACKAGES`), importing or exporting configuration files you pick yourself, and an optional app lock (PIN / biometric) that is stored only as a salted hash on your device.

Besides the tunnel itself, the app makes network connections only when you ask it to: fetching or refreshing a configuration or subscription from a URL you supply, briefly contacting listed endpoints to measure latency (`ping`), or contacting a subscription URL you provide. Operators of those endpoints can see standard connection metadata such as your IP address and access time under their own policies; those endpoints are not developer telemetry.

You can remove everything the app holds by using the reset option inside the app, by clearing the app data in Android Settings, or by uninstalling the app.

## Log Data

The app shows a connection log so you can diagnose a failed connection yourself. That log may contain the server address you entered, timestamps, and technical messages from the connection engine. It is kept on your device only and is not transmitted to us.

We do not embed any crash-reporting or general usage-analytics SDK of our own. Off-device processing performed by us is limited to the optional subscription/configuration fetch described above. Advertising diagnostics are handled by Google as described in the Advertising section, plus whatever Android or Google Play collects under your own device settings.

## Cookies

Our app is not a web browser and sets no cookies of its own, so there is no cookie banner inside it. The ads it displays are rendered by the Google Mobile Ads SDK, which may use cookies or similar identifiers as part of the ad content.

Those identifiers belong to that SDK rather than to us, so we cannot offer an in-app switch for them. They are controlled in two places instead:

- Where consent is legally required — the European Economic Area, the United Kingdom, and Switzerland: through the consent form shown on first launch, and afterwards through the "Ad privacy options" entry in the app settings (shown only in those regions).
- On any device, anywhere: in Android Settings, under Google and then Ads, where you can delete or reset your advertising ID. Deleting it turns off ad personalization for every app on the device, including ours.

The ads themselves cannot be switched off, because the app is free and paid for by advertising. What you can decide is whether those ads are personalized.

## Service Providers

We do not sell user data or provide it to data brokers or independent analytics vendors. Third-party components embedded in our app include Google Play Services and the Google Mobile Ads SDK.

What those components collect is described in the Advertising section below. How Google then handles it is governed by Google's own privacy policy and terms, not by an arrangement we control, and we are not able to access, correct, or delete data that Google holds.

## Advertising

Our app is supported by ads served through Google AdMob (the Google Mobile Ads SDK). As a third party, that SDK collects data and shares it with Google in order to deliver, measure, and protect ads. This happens inside the SDK rather than through code we write, and we never receive a copy of the data.

The data the SDK collects and shares falls into four categories: device or other identifiers (the advertising ID and the app set ID); approximate location, estimated from your IP address; app interactions, such as app opens, taps, and ad/video views; and diagnostics about app performance, such as launch time, hang rate, and energy usage. It is used for advertising and marketing, analytics, and fraud prevention, security, and compliance, and it is encrypted in transit.

Precise location is never requested: our app does not ask for any location permission. The `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION` permissions are declared only for Wi-Fi SSID detection used by the optional auto-connect-on-untrusted-WiFi feature, and are not used for advertising or location tracking.

If you are in the European Economic Area, the United Kingdom, or Switzerland, a consent form is shown before personalized ads appear, and in those regions the app settings show an "Ad privacy options" entry so you can change your choice at any time. On any device you can also reset or delete your advertising ID from Android Settings, under Google and then Ads.

- [How Google uses data from apps that use its services](https://policies.google.com/technologies/partner-sites)

## Security

We value your trust, so the data our app keeps on your device is encrypted at rest, and connections to the servers you configure use the encryption offered by the protocol you select (SSH, VMess/VLESS/REALITY, Trojan, Shadowsocks, WireGuard, OpenVPN, Hysteria2, SlowDNS, Psiphon). No method of transmission over the internet and no method of electronic storage is 100% secure, so we cannot guarantee absolute security.

## Links to Other Sites

Our app may contain links to other sites (for example subscription or configuration sources you add). If you click a third-party link, you will be directed to that site. Those external sites are not operated by us, so we strongly advise you to review their privacy policies. We have no control over, and assume no responsibility for, the content, privacy policies, or practices of any third-party site or service.

## Children's Privacy

Our app is not directed to anyone under the age of 13, and we do not knowingly collect personal information from children. If we learn that a child's data is held, a parent or guardian may contact us to request deletion of any matching data that is still available.

Data stored locally can be removed with the reset option, by clearing app data in Android Settings, or by uninstalling the app. Advertising data is held by Google and is controlled through Google settings and policies.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time, for example when the app gains a feature that needs a new permission. You are advised to review this page periodically. We will notify you of any change by publishing the new policy on this page, and changes take effect as soon as they are published here.

## Contact Us

If you have any question or suggestion about this Privacy Policy, contact us at **moodesigner.99@gmail.com** (HighSpeedStudios).
