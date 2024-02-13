## An Application for BlockChain developed in Rust Programming Language 

This is specifically a Blockchain application that is developed using the pragmatic, intuitive and rather efficient Rust programming language, a language renowned for its performance and safety, particularly in the realm of concurrent programming.

### Resources for the Application

The baseline for this application was forked, cloned or duplicated from an existing code-based resource known as the substrate-node-template. It's a readily available template that aids in quicker and easier blockchain development without necessarily starting from scratch. To get a holistic view of this template, you can access it from this specific GitHub link: <br/>
https://github.com/substrate-developer-hub/substrate-node-template. <br/>
The link will direct you to a GitHub repository from the Substrate Developer Hub where this node template resides.

### Important Amendments and Updates

Most renovations and tweaks have been rather focused—a lion's share of the attention has been tilted towards pallets and runtime libraries. Pallets are essentially special modular plugins, which in our case aid in customization and swift development of the Blockchain application. On the other hand, the runtime libraries, commonly abbreviated as runtime libs, provide a low-level platform for creating powerful applications. Both components are crucial in ensuring efficient functionality of the Blockchain application.

### Mode of Deployment 

The deployment strategy for the Blockchain application built with Rust will be through Docker. Docker deployment is lauded for its ability to ensure consistency across multiple development, staging, and production environments amongst its many benefits. This means our Blockchain application will be lightweight, stand-alone, executable package that includes everything needed to run it: code, runtime, system tools, system libraries, and settings. This makes it possible to run the blockchain application on any kind of platform or cloud without worry of compatibility issues.