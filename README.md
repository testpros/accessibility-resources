# Summary 

This is a frequently updated collection of accessibility resources put together by [TestPros Inc](https://www.testpros.com). Please feel free to contribute to the list, suggest additional resources, and/or identify broken links by submitting an issue or PR. 

#Standards and Guidelines
    - [Web Content Accessibility Guidelines 2.0](https://www.w3.org/TR/WCAG20/) - w3c accessibility standard still most widely in use, even though WCAG 2.1 has been finalized
    - [Web Content Accessibility Guidelines 2.1](https://www.w3.org/TR/WCAG21/) - Updated guidelines with additional success criteria for mobile devices
    - [W3C Web Accessibility Iniitative (WAI)](https://www.w3.org/WAI/) - Fantastic resource for content writers, designers, developers, evaluators, managers, policy makers, trainers, users, and more. Highly recommended.    
    - [Section 508 Revised Standards](https://www.access-board.gov/guidelines-and-standards/communications-and-it/about-the-ict-refresh/final-rule/text-of-the-standards-and-guidelines) - United States Access Board standards for complying with Section 508
    - [DHS Trusted Tester v5 Conformance Test Process for Web](https://section508coordinators.github.io/TrustedTester/) - Extensive test process that is quickly being considered standard within the U.S. federal government.

# Automated / Psuedo-manual Testing Tools
    - [aXe](https://github.com/dequelabs/axe-core) - Automated accessibility testing tool developed by Deque; Node CLI; Ruby Gems; Selenium Webdriver; JUnit/Selenium; Grunt Webdriver; Chrome, Edge, Firefox, Safari, and IE support 
    - [aXe for ReactJS](https://www.npmjs.com/package/@axe-core/react) - aXe engine for React applications (may be deprecated)
    - [Accessibility Insights](https://accessibilityinsights.io/) - Developed by Microsoft. Android, Chrome, and Windows Desktop application tools with automated testing functionality (using aXe as the engine) and a great walk-through for manual portions of WCAG guidelines
    - [ANDI](https://www.ssa.gov/accessibility/andi/help/install.html) - Tool developed by the Social Security Administration. Performs automated accessibility checks as well as helps to facilitate manual testing via capabilities such as a visual representation of expected screen reader output.
    - [WAVE](https://wave.webaim.org/extension/) - Automated accessibility testing tool; Browser extension(s), Standalone API, and subscription based API (can cost 💵 depending on service used, but generally free)
    - [HTML Code Sniffer](https://github.com/squizlabs/HTML_CodeSniffer) - Free and open source automated tool. Node CLI based using Puppeteer and PhantomJS. Tests against WCAG 2.1 and Section 508.
    - [iOS Accessibility Inspector](https://developer.apple.com/library/archive/technotes/TestingAccessibilityOfiOSApps/TestingtheAccessibilityofiOSApps/TestingtheAccessibilityofiOSApps.html) - iOS Developer Tool for performing accessibility testing of applications via iOS Simulator

# CI/CD
    - [pa11y](https://pa11y.org/) - Great tool that uses aXe and/or HTML Code Sniffer from a web-based dashboard, CLI, webservice, and/or CI integration 
    - [koa11y](https://github.com/open-indy/Koa11y) - Desktop application for automatic accessibility testing (uses pa11y as engine)
    - [IBM Equal Access](https://github.com/IBMa/equal-access) - Free and open source toolset maintained by IBM. Chrome and Firefox extensions, Node CLI, Karma, and Cypress integration

# Screenreaders
    - [NVDA](https://www.nvaccess.org/download/) - Capable free and open source screen reader
    - [JAWS](https://www.freedomscientific.com/products/software/jaws/) Very capable screen reader, but very expensive 💵
    - [TalkBack (Android)](https://support.google.com/accessibility/android/answer/6283677?hl=en) - Android screen reader (among other capabilities) available in Play Store 
    - [VoiceOver (IOS)](https://www.apple.com/accessibility/iphone/vision/) - Apple's iOS native screen reader (among other capabilities)

# Additional Tools
    - [Color Contrast Checker](https://webaim.org/resources/contrastchecker/) - Tool for checking the contrast between background and foreground colors and the level of WCAG compliance (e.g., A / AA / AAA)

# Additional Resources
    - [Voluntary Product Accessibility Template 2.4](https://www.itic.org/policy/accessibility/vpat) - Industry standard template for giving high-level overview of the accessibility of information and communications technology (ICT). Frequently required as part of government procurements.
    - [Section 504 of the Rehabilitation Act of 1973](https://dredf.org/legal-advocacy/laws/section-504-of-the-rehabilitation-act-of-1973/) - U.S. Legal requirement for any organization receiving federal funding (e.g., public schools, educational institutions such as universities, state and local governments, etc.) to be accessible
    - [Title III of the Americans with Disabilities Act](https://www.ada.gov/taman3.html) - U.S. Legal requirement for places of public accomodation to be accessible
    - [Section508.gov](https://www.section508.gov/) - U.S. Legal requirement for federal agencies to be accessible; Also great resource for how to comply with Section 508 on a variety of types of physical and virtual technologies
    - [EN 301 549](http://mandate376.standards.eu/) - European accessibility standards / requirements
    - [Accessibility for Ontarians with Disabilities Act](https://www.aoda.ca/) - Canadian accessibility standards / requirements
    - [Robles v. Domino's Pizza LLC](https://casetext.com/analysis/ninth-circuit-reinforces-accessibility-requirement-for-websites-and-apps-under-ada?PHONE_NUMBER_GROUP=C&sort=relevance&resultsNav=false&q=) - Key court case in the Ninth Circuit Court of Appeals establishing ADA Title III applicability to commercial digital properties for places of public accomodation. Supreme Court declined to hear appeal, thus leaving Ninth Circuit Court of Appeals decision as precedent
    - [DHS Trusted Tester v5 Training and Certification](https://training.section508testing.net/) - Excellent computer based curriculum and certification opportunity offered free of charge by the Department of Homeland Security, Office of Accessible Systems and Technology.
