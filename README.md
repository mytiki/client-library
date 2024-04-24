# Client Library
The Client Library is designed to simplify the integration of applications with mytiki.com APIs.

By leveraging the TIKI Publish Client Library, developers can streamline the process of authorization, licensing, data capture,  upload, and more, significantly reducing the complexity of connecting their applications to mytiki.com.

## Key Features

- **Simplified Integration**: The Client Library abstracts away the complexities of interacting with mytiki.com APIs, offering convenient methods for common tasks such as authentication, licensing, and data upload.

- **Platform Compatibility**: Whether you're developing a web app, an Android app, or an iOS app, the Client Library provides seamless integration options for various platforms.

- **Flexible Configuration**: The library offers flexible configuration options, allowing developers to tailor the integration to their specific use cases by providing parameters for pre-built templates, such as company name, jurisdiction and its own terms of service.

## Optional Features

- **Camera Integration**: Developers can leverage the optional camera integration feature to enable scanning physical receipts directly from mobile devices, enhancing the user experience of receipt capture.
- **Email Scraping**: The Gmail and Outlook integrations provides an easy interface to connect e-mail accounts to the client library and scrape receipt e-mails from a pre-defined list of known receipt senders.

## How it Works
The TIKI cloud infrastructure boasts HTTP REST APIs, seamlessly compatible with any standard HTTP client for effortless request handling and response management.

Our Client Library serves as an intuitive interface for engaging with the TIKI REST APIs. By handling API authentication and data uploads, it streamlines processes, minimizing the need for extensive code writing across Android, iOS, and Capacitor applications.

Moreover, it goes beyond API interaction, offering features that streamline integration with third-party APIs and services, enabling the implementation of various functionalities:

- Receipt Scan: Integrate with the device's camera to effortlessly capture pictures of physical receipts.
- E-mail Receipt Scraping: Authenticate with the Gmail API to streamline the download of receipt emails from known senders, significantly enhancing email scraping efficiency.
- Device Permissions Management: Control device permissions and monitor user consent using a simple, ready-to-use API.

While the client library offers numerous integrations, each one remains entirely optional and separate from the others. Users can leverage the library to communicate with the TIKI REST APIs without implementing any of the receipt scan, email scraping, or device permissions features.

## Get Started
Select your platform to get started:

- [Android](https://github.com/mytiki/client-library-android)
- [iOS](https://github.com/mytiki/client-library-ios)
- [Capacitor](https://github.com/mytiki/client-library-capacitor)

View the complete docs at [docs.mytiki.com](https://docs.mytiki.com/reference/client-library-overview)
