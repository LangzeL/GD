# COMP30022 IT Project - Team006 LongBeachPlace Website Product Report

--------------

## Table of Contents

- [Executive Summary](#executive-summary)
- [Introduction](#introduction)
- [Website Developing Work Progress](#website-developing-work-progress)
  - [Planning and Analysis](#planning-and-analysis)
  - [Development](#development)
  - [Testing](#testing)
  - [Deployment](#deployment)
- [Design and User Experience](#design-and-user-experience)
  - [User Interface Design](#user-interface-design)
  - [Accessibility and Responsiveness](#accessibility-and-responsiveness)
- [Features and Functionality](#features-and-functionality)
  - [Core Features](#core-features)
  - [Additional Features](#additional-features)
- [Challenges and Solutions](#challenges-and-solutions)
- [Project Management and Collaboration](#project-management-and-collaboration)
  - [Team Structure](#team-structure)
  - [Communication](#communication)
  - [Version Control](#version-control)
- [User Documentation and Support](#user-documentation-and-support)
- [Conclusion and Future Work](#conclusion-and-future-work)
- [Appendices and References](#appendices-and-references)

----------------

## Executive Summary

As a part of the COMP30022 IT Project, our team, Team006, started on the journey of developing the LongBeachPlace website. Our mission was simple yet ambitious: to create a platform that was not only visually appealing and user-friendly but also robust and adaptive to different user needs.

From the outset, our objectives were clear. We aimed to build a website that would serve as a central hub for LongBeachPlace, facilitating a seamless user experience while providing comprehensive functionality for content management. To achieve this, we leveraged modern web technologies and embraced an Agile approach that allowed for flexibility and responsiveness to feedback throughout the development process.

The development was not without its hurdles. We encountered challenges, particularly in integrating a responsive design that would cater to both desktop and mobile users. The issue of creating an intuitive content management system also posed significant complexity. However, through a combination of team brainstorming sessions and consultation with our project mentors, we formulated solutions that not only resolved these issues but also enhanced the overall product.

The fruit of our labor is a website that stands out for its ease of navigation, aesthetic clarity, and responsive design. Its features, such as the dynamic content slider and the event management system, were developed with the end-user in mind, ensuring that visitors could access and interact with the site with minimal effort and maximum satisfaction.

As we look to the future, we are excited about the roadmap we've laid out for LongBeachPlace. Our plans include rolling out a user feedback system and integrating e-commerce functionalities, which we believe will further enrich the user experience and the client's business operations.

In wrapping up this project, we've not only delivered a product that we're proud of but also gained invaluable experience in teamwork, problem-solving, and technical development. This project is a testament to our team's commitment and hard work, and we are confident that it will fulfill, if not surpass, the expectations of both our client and the end-users.

------------

## Introduction

Our project's inception began with a clear mandate from Longbeach Place: to create a simple yet welcoming website that would attract a broad demographic, with a focus on middle-aged to younger users. The primary purpose was to present a general introduction to the company and its offerings in an engaging and modern interface.

Central to our development efforts was the client's vision for a website that was not just functional but also user-friendly and accessible. The desired outcome was a platform that felt fresh and modern, with particular attention to aesthetics and user experience. To this end, we were tasked with creating a comprehensive course booking system, a calendar for events, and a membership area complete with registration, login, and logout functionalities.

Our responsibilities extended to backend features critical for the organization's operations, such as an information storage system, a notification setup to alert users, and a check-in system for tracking attendance, possibly through QR codes. Additionally, the website needed to facilitate updates to user info and status, including links to social media and email.

The client's requirement for a crisp, modern-looking design was paired with specific functionalities like text-to-audio accessibility features, content pages, and integrated payment systems for room hires and donations. We were also encouraged to explore innovative features like reminder messages for waitlists and cancellations, potentially extending to an app to showcase Longbeach Place to a wider audience.

In this report, we delve into how our team interpreted these initial requirements, the subsequent updates we received, and how we translated them into a cohesive website that aligns with the client's objectives and user needs.

-------

## Website Developing Work Progress

### Planning and Analysis

At the inception of the Longbeach Place website project, our team, Team006, committed to a rigorous planning and analysis phase. This foundational step was crucial to align our development trajectory with the client's expectations and the users' needs

**Planning stage**

Our planning began with a kickoff meeting where we detailed the client's vision and established a project timeline. By reviewing initial requirement provide by client and the first zoom meeting, we form a robust understanding of the required features, design aesthetics, and functional components. Recognizing the client's emphasis on a modern and accessible platform, we outlined a technology stack that would facilitate a responsive and adaptive website.

**Client Requirements:**

- **Website Purpose:**
  - Create a simple, welcoming website to attract a diverse audience, focusing on middle-aged to younger demographics.
  - Provide a general introduction to Longbeach Place, its mission, and services.
- **User Experience:**
  - Develop a functional and user-friendly interface.
  - Ensure the website is fresh, modern, and accessible, with text-to-audio features for enhanced accessibility.
- **Design Aesthetics:**
  - Maintain a consistent layout throughout the website.
  - Use preferred color schemes, specifically avoiding bright orange and incorporating darker colors and pink.
  - Implement a dynamic content slider and event management system.
  - Redesign elements like the 'Contact Us' section with a blue background.
- **Functional Requirements:**
  - Back-end information storage system.
  - Notification system for updates.
  - Attendance check system with QR code capabilities.
  - User information update functionalities, including social media and email links.
  - A course booking system integrated with a calendar.
  - A membership area for registration and login/logout processes.
  - Payment gateway for room hires and donations.
  - Admin functionalities to update text, layout, images, etc.
- **Specific Features:**
  - Sponsors section to be labeled as "Supported By" with smaller logos.
  - Contact information, including phone, email, and social media links, should be clearly visible.
  - Subscription option for newsletters.
  - Reminder messages for waitlists, cancellations, etc.
  - Explore the potential for a mobile application.
- **Technical and Backend:**
  - A simple admin type without the need for multiple levels.
  - Database setup to accommodate the aforementioned features.
- **Miscellaneous:**
  - Responsive design for mobile and desktop.
  - Members and staff/tutor login portal with customized colors.
  - Admin login at the very bottom of the page.

| Category                    | Requirements                                                 |
| --------------------------- | ------------------------------------------------------------ |
| **Website Purpose**         | - Create a simple, welcoming website to attract a diverse audience. |
|                             | - Provide a general introduction to Longbeach Place, its mission, and services. |
| **User Experience**         | - Develop a functional and user-friendly interface.          |
|                             | - Ensure the website is fresh, modern, and accessible, with easier function to maintain the website. |
| **Design Aesthetics**       | - Maintain a consistent layout.                              |
|                             | - Use preferred color schemes, avoiding bright orange and incorporating darker colors and pink. |
|                             | - Implement a dynamic content slider and event management system. |
|                             | - Redesign the 'Contact Us' section with a blue background.  |
| **Functional Requirements** | - Back-end information storage system.                       |
|                             | - Notification system for updates.                           |
|                             | - Attendance check system with QR code capabilities.         |
|                             | - User information update functionalities, with social media and email links. |
|                             | - A course booking system integrated with a calendar.        |
|                             | - A membership area for registration and login/logout processes. |
|                             | - Payment gateway for room hires and donations.              |
|                             | - Admin functionalities to update text, layout, images, etc. |
| **Specific Features**       | - Sponsors section labeled as "Supported By" with smaller logos. |
|                             | - Visible contact information, including phone, email, and social media links. |
|                             | - Subscription option for newsletters.                       |
|                             | - Reminder messages for waitlists, cancellations, etc.       |
|                             | - Explore the potential for a mobile application.            |
| **Technical and Backend**   | - A simple admin type without the need for multiple levels.  |
|                             | - Database setup to accommodate the features listed.         |
| **Miscellaneous**           | - Responsive design for mobile and desktop.                  |
|                             | - Members and staff/tutor login portal with customized colors. |
|                             | - Admin login at the very bottom of the page.                |

As the page content group, our focus was primarily on ensuring that the content management aspect of the website was intuitive and efficient, allowing for easy updates and maintenance. This involved designing a user-friendly backend system that could handle dynamic content changes, such as new course offerings or event updates, without requiring technical expertise from the Longbeach Place staff. Below is an image example of what client want the frontend design to contains and look:-

![client‘s requirement](Diagram/client‘s%20requirement.png)

![colour pref](Diagram/colour%20pref.png)

**Development**

In the development phase of the Longbeach Place website, our primary focus was to materialize the client's vision into a functional and visually appealing digital platform. Key among these requirements was the design of the menu bar and the overall color scheme, which we approached with a combination of creative design and technical proficiency. The image below can serve as a reference point for the aesthetic and functional elements that our team design and need to incorporate into the Longbeach Place website.

![homepage design](Diagram/homepage%20design.png)![homepage design 2](Diagram/homepage%20design%202.png)

**Menu Bar Design**

Understanding the crucial role of navigation in user experience, we invested significant effort in designing the menu bar. The client's call for simplicity and intuitiveness was at the forefront of our design process. We crafted a sleek and straightforward menu bar that complemented the website's overall aesthetic and facilitated ease of navigation. Structured to offer immediate access to all primary sections of the website, this menu bar ensures that users can locate their desired information effortlessly. The GIF below showcases the final version of the menu bar, featuring a built-in dropdown menu that allows users to navigate to their chosen section with a single click.

![menubar demo](Diagram/menubar%20demo.gif)

**Color Scheme Implementation**

The color scheme was a pivotal element in our development efforts, with the client expressing a strong preference for vibrant, beach-inspired colors such as sunny yellows and bright blues. To align with this vision of bringing the essence of the beach to the digital space, our design team undertook a thoughtful process of color selection. We aimed to capture the warmth and relaxation associated with Longbeach Place, resulting in a palette that was both inviting and reflective of the seaside setting.

In pursuit of the perfect beach-themed aesthetic, we developed five distinct color scheme versions. Each iteration was an exploration in hues and tones, drawing inspiration from the sun, sand, and sea. We paid particular attention to areas of the website for the background, we don't want the background to be full white(#FFF) as the bright white would hurt user's eye's when reading, therefore we select a softer white to remain the fresh look in the website but not too high contrast.

![version 1](Diagram/version%201.png)![version 2](Diagram/version%202.png)![version 3](Diagram/version%203.png)![version 4](Diagram/version%204.png)![version 5](Diagram/version%205.png)

After presenting all versions to the client, we engaged in a collaborative selection process. The final choice was the second color scheme that best encapsulated the lively and refreshing ambiance of the beach, enhancing the website's visual appeal while meeting the client's specific requirements. This chosen palette now adorns the website, contributing to a consistent and thematic user experience that visitors can enjoy.

**Editor function**

With the client's requirements for a dynamic and easily updatable website in mind, we turned our attention to the development of the edit function, a key feature that would empower the Longbeach Place team to maintain and refresh their content as needed. For this critical component, we chose Grape.js, an open-source web builder framework that's known for its flexibility and user-friendliness.![example grapejs](C:\Users\anson\Documents\GitHub\GD\Diagram\example grapejs.png)

[^figure 1]: example of grape.js UI

Grape.js presented us with the tools necessary to build a custom editing interface from the ground up. The framework's drag-and-drop functionality allowed us to design a system where the user can intuitively manipulate page elements without any knowledge of coding. This interface includes a variety of features:

- **Customizable Layouts**: Users can easily adjust the layout to accommodate new content, ensuring the site remains visually engaging and informationally current.
- **Style Manager**: Grape.js's style manager was utilized to give users the ability to change styling properties, like fonts and colors, aligning with the website's beach-inspired theme.
- **Asset Manager**: Implementing an asset manager made managing images and other media straightforward, streamlining the process of updating visual content.
- **Responsive Design Preview**: We integrated a feature that allows the client to preview their changes in real-time across different device sizes, ensuring the website's responsiveness.
- **Content Blocks**: Predefined blocks of content can be dragged onto the canvas, making page updates and creation as simple as piecing together a puzzle.

During development, we iterated over several prototypes, refining the UI/UX until it met our standards for ease of use. We conducted user testing sessions with the Longbeach Place staff to gather feedback and further polish the editing experience. The final product is an edit function that is not only powerful and versatile but also approachable for users of all technical backgrounds.

The below gif is a short demo demonstrating how editor work

![editor](C:\Users\anson\Documents\GitHub\GD\Diagram\editor.gif)

Furthermore, to streamline the content update process, we engineered a solution to convert our React JSX code into HTML for storage in the database. This translation allowed for the admin's content changes to be directly saved in a format that could be readily served to the website.

For instance, every time user did a change in the website, the database will immediate received an update

![saved](Diagram/saved.png)

![mongodbsaved](C:\Users\anson\Documents\GitHub\GD\Diagram\mongodbsaved.png)

Upon completion of edits through the Grape.js interface, the updated content—now in HTML format—is committed to the database. This approach ensures that any modifications made by the admin are not only saved securely but are also immediately reflected in the backend.

![Admin Interactions with Website Editor (Sequence Diagram)](C:\Users\anson\Documents\GitHub\GD\Diagram\Admin Interactions with Website Editor (Sequence Diagram).png)

[^figure 2]: uml diagram of editor function

The next step in the process involves retrieving the updated HTML from the database and rendering it back on the website. Our backend services, designed to work seamlessly with the React framework, fetch the revised content and update the website in real-time. This system provides a robust and efficient mechanism for content management, allowing for changes to be pushed live without any additional steps or technical intervention.

This methodology not only maintains the integrity and performance of the website but also affords the admin the flexibility to manage content dynamically. It embodies a seamless integration between the frontend and backend, culminating in a cohesive user experience both for the admin editors and the end-users visiting the Longbeach Place website.

In deploying Grape.js, we ensured that the Longbeach Place website remains a living entity, capable of evolving alongside the community it serves. The edit function stands as a testament to our dedication to providing a sustainable and self-sufficient digital solution.



---------

## Testing

### User Stories:

- **New Visitor**: As a new visitor, I want to understand what LongBeach Place Inc. is, where is LongBeach Place Inc. and the events or activities LongBeach Place Inc. operates.
- **Potential Donor**: As a potential donor, I want to see the annual statement or report of LongBeach Place Inc. The success stories and data that demonstrate LongBeach Place Inc. are also desired.
- **Potential Volunteer**: As a potential volunteer, I want to quickly find out how I can get involved and contribute to the LongBeach Place Inc..
- **Current Member**: As a current member, I want to book or change my appointments and hire the room through an easy-to-use interface. Furthermore, I want to know what events are happening in LongBeach Place Inc..
- **Stakeholder**: As a stakeholder, I want to provide and view feedback about the LongBeach Place Inc.'s services and initiatives.
- **Partner**: As a partner, I want to access showcases, contact details and official statements easily.
- **User**: As a user, I expect the site to be accessible on mobile, tablet and desktop devices, with an intuitive and rationalised layout.

### Requirements:

- Home page with a clear navigation bar for easily access.
- An illustrative page contains LongBeach Place Inc.'s official information.
- Dynamic activities and events section with photos and quotes.
- A dedicated volunteer section with sign-up forms and information.
- A user-friendly appointment booking system.
- An accessible feedback form and display section.
- A contact page with organization details, media kits, and official statements.
- A responsive design that ensures usability across devices.

### Test Plan:

Based on the user stories and requirements defined above, three types of tests would be continuously conducted on the Website throughout the whole development process.

### 1. UI/UX Test

Given the context of the LongPlaceBeach Inc., ensuring the consistent and accurate presentation of information is paramount. The website would likely undergo several changes over time - updates to events details, activities information, and possibly design tweaks. Every change, even if minor, has the potential to unintentionally disrupt the UI/UX.

- **Objective**: Ensure that the website is intuitive, user-friendly, and aesthetically pleasing.

For UI/UX test, the Visual Regression Testing strategy will be adopted. It will ensures that changes to the user interface (whether expected or unintentional) are captured and reviewed. It makes sure the interface looks correct after code modifications.

Therefore, **BackstopJS** will be used as the tool for visual regression testing. The users can create a series of screenshots representing the "correct" appearance of your app or website. Then, every time you make changes, **BackstopJS** captures the screenshots again and compares them with the **reference screenshots**. This will detect the unexpected UI changes by highlighting visual discrepancies.

- During the development of the website, the visual regression testing will be conducted in every team member's **local development environment**, after they have make changes to the UI/UX of the website. The result will be demonstrated in the console output of the terminal and default browser.

#### UI/UX Testing process

1. Use **BackstopJS** to generate a set of **stable versions** of bitmaps as the reference.

   ```
   backstop reference
   ```

   

2. **After making changes to the UI/UX of the website**, check the comparison of reference and test screenshots generated by **BackstopJS** and ensure the modification is suitable and accessible from various devices.

   ```
   npm run test:backstop
   ```

   

   - The comparision will be conducted through multiple devices, ensure the responsive design: [![UI/UX Test error image 4](Testing%20Plan/UIUX%20Test/4.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/UIUX Test/4.png) [![UI/UX Test error image 5](Testing%20Plan/UIUX%20Test/5.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/UIUX Test/5.png) [![UI/UX Test error image 6](Testing%20Plan/UIUX%20Test/6.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/UIUX Test/6.png) [![UI/UX Test error image 7](Testing%20Plan/UIUX%20Test/7.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/UIUX Test/7.png)
   - The discrepancies will be highlighted: [![UI/UX Test error image 8](Testing%20Plan/UIUX%20Test/8.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/UIUX Test/8.png) [![UI/UX Test error image 9](Testing%20Plan/UIUX%20Test/9.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/UIUX Test/9.png) [![UI/UX Test error image 10](Testing%20Plan/UIUX%20Test/10.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/UIUX Test/10.png) [![UI/UX Test error image 11](Testing%20Plan/UIUX%20Test/11.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/UIUX Test/11.png)

3. **After checking the report**, if teams accept the modifications to the UI/UX of the website, the **BackstopJS** will be used to generate a new set of bitmaps as the new reference to update the reference data in the Backstop. This is for the next iteration of UI/UX testing; step one can be skipped for the next time's UI/UX testing.

4. Check the comparison of reference and test screenshots again, ensure the modifications have been deployed successfully and check the accessibility of the website.

   - All the comparisons will be passed, and there will be no errors. [![UI/UX Test correct image 1](Testing%20Plan/performance-testing/1.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/UIUX Test/1.png) [![UI/UX Test correct image 2](Testing%20Plan/performance-testing/2.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/UIUX Test/2.png) [![UI/UX Test correct image 3](Testing%20Plan/performance-testing/3.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/UIUX Test/3.png)

### 2. Performance Test

Within the backdrop of the LongPlaceBeach Inc. website, prompt and efficient access to vital information, such as event dates, volunteering sign-ups, and donation methods, is crucial. As LongPlaceBeach Inc. grows and the site garners more traffic, slowdown or inefficiency could hinder the user experience, potentially leading to lost valuable opportunities.

- **Objective**: Ensure the website loads quickly, handles multiple users and remains stable under stress.

Performance testing ensures the website remains agile and efficient, even during peak traffic. Simulating various user loads and testing different aspects of the website's performance will ensure that every visitor, such as potential donors, volunteers, members, etc., has a seamless and optimal browsing experience.

**Lighthouse** will be adopted for the LongPlaceBeach Inc. website's performance Test tool. It can provide comprehensive insights into how the website performs, looking at metrics crucial for user experience like site load time, interactivity, and content stability as it loads. Beyond that, the actionable feedback on improving performance makes it outstanding from other tools.

#### Performance Testing process

1. The performance testing integrates within a **CI/CD framework**. After pushing the modifications to the git repository, every content update, design tweak, or feature addition is reviewed and passes automated tests.

```
  performance-testing:
    needs: [deploy-backend, deploy-frontend]
    runs-on: ubuntu-latest

    steps:
    - name: Install lighthouse
      run: npm install -g lighthouse
    
    - name: Create Lighthouse output directory
      run: mkdir -p performance_testing

    # Run lighthouse test
    - name: Run Lighthouse Performance Test
      run: lighthouse "https://longbeachfrontend-0adcfe405469.herokuapp.com/" --chrome-flags="--headless" --output=json --output-path=./performance_testing/testing-report.json
    
    - name: Upload Lighthouse Report
      uses: actions/upload-artifact@v2
      with:
        name: performance-testing-report
        path: ./performance_testing/testing-report.json
```



[![Performance Test image 1](Testing%20Plan/performance-testing/1.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/performance-testing/1.png) [![Performance Test image 2](Testing%20Plan/performance-testing/2.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/performance-testing/2.png)

1. After the testing, the report will be uploaded to the **Artifacts**. It will be downloaded and reviewed to ensure the website's compatibility and functionality.

[![Performance Test image 3](Testing%20Plan/performance-testing/3.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/performance-testing/3.png)

- Performance testing report

```
{
"lighthouseVersion": "11.2.0",
"requestedUrl": "https://longbeachfrontend-0adcfe405469.herokuapp.com/",
"mainDocumentUrl": "https://longbeachfrontend-0adcfe405469.herokuapp.com/",
"finalDisplayedUrl": "https://longbeachfrontend-0adcfe405469.herokuapp.com/",
"finalUrl": "https://longbeachfrontend-0adcfe405469.herokuapp.com/",
"fetchTime": "2023-10-19T16:33:31.885Z",
"gatherMode": "navigation",
"runWarnings": [],
"userAgent": "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) HeadlessChrome/118.0.5993.70 Safari/537.36",
"environment": {
   "networkUserAgent": "Mozilla/5.0 (Linux; Android 11; moto g power (2022)) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/109.0.0.0 Mobile Safari/537.36",
   "hostUserAgent": "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) HeadlessChrome/118.0.5993.70 Safari/537.36",
   "benchmarkIndex": 1304.5,
   "credits": {
      "axe-core": "4.8.2"
   }
},
"audits": {
   "is-on-https": {
      "id": "is-on-https",
      "title": "Uses HTTPS",
      "description": "All sites should be protected with HTTPS, even ones that don't handle sensitive data. This includes avoiding [mixed content](https://developers.google.com/web/fundamentals/security/prevent-mixed-content/what-is-mixed-content), where some resources are loaded over HTTP despite the initial request being served over HTTPS. HTTPS prevents intruders from tampering with or passively listening in on the communications between your app and your users, and is a prerequisite for HTTP/2 and many new web platform APIs. [Learn more about HTTPS](https://developer.chrome.com/docs/lighthouse/pwa/is-on-https/).",
      "score": 1,
      "scoreDisplayMode": "binary",
      "details": {
      "type": "table",
      "headings": [],
      "items": []
      }
   },
   "viewport": {
      "id": "viewport",
      "title": "Has a `<meta name=\"viewport\">` tag with `width` or `initial-scale`",
      "description": "A `<meta name=\"viewport\">` not only optimizes your app for mobile screen sizes, but also prevents [a 300 millisecond delay to user input](https://developer.chrome.com/blog/300ms-tap-delay-gone-away/). [Learn more about using the viewport meta tag](https://developer.chrome.com/docs/lighthouse/pwa/viewport/).",
      "score": 1,
      "scoreDisplayMode": "metricSavings",
      "warnings": [],
      "metricSavings": {
      "INP": 0
      },
      "guidanceLevel": 3
   },
   "first-contentful-paint": {
      "id": "first-contentful-paint",
      "title": "First Contentful Paint",
      "description": "First Contentful Paint marks the time at which the first text or image is painted. [Learn more about the First Contentful Paint metric](https://developer.chrome.com/docs/lighthouse/performance/first-contentful-paint/).",
      "score": 0.95,
      "scoreDisplayMode": "numeric",
      "numericValue": 1527.738,
      "numericUnit": "millisecond",
      "displayValue": "1.5 s",
      "scoringOptions": {
      "p10": 1800,
      "median": 3000
      }

      // Other sections of report ...
```

### 3. Penetration Test

Due to the LongPlaceBeach Inc. website might be handling the sensitive data, such as from feedback forms to potential donation details. The sanctity and security of this data cannot be overemphasized. Users trust LongPlaceBeach Inc. with their information, and any security breach could tarnish LongPlaceBeach Inc.'s reputation and become an obstacle to future development.

- **Objective**: Ensure the website is secure from common vulnerabilities and threats.

Penetration testing can conduct regular security audits to identify potential threats. Mainly focus on testing probes the website and associated databases for vulnerabilities that malicious entities could exploit.

Hence, **OWASP ZAP** will be adopted as the tool for penetration Tests. It can provide detailed information on potential vulnerabilities and offers passive and active scanning capabilities to identify threats.

#### [Penetration Testing process](https://github.com/LangzeL/GD/edit/main/README.md#penetration-testing-process)

1. The penetration Testing integrates within a **CI/CD framework**. After pushing the modifications to the git repository, all updates, tweaks, and feature additions are reviewed and systematically tested.

```
  penetration-testing:
    needs: [deploy-backend, deploy-frontend]
    runs-on: ubuntu-latest

    steps:
      - name: Checkout
        uses: actions/checkout@v2

      - name: Run OWASP ZAP Scan
        uses: zaproxy/action-baseline@v0.9.0
        with:
          token: ${{ secrets.GH_PAT }}
          docker_name: 'ghcr.io/zaproxy/zaproxy:stable'
          target: 'https://longbeachfrontend-0adcfe405469.herokuapp.com/'
          artifact_name: penetration-testing-report
          rules_file_name: '.zap/rules.tsv'
          cmd_options: '-a'
```



[![Penetration Test image 1](Testing%20Plan/penetration-testing/1.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/penetration-testing/1.png) [![Penetration Test image 2](Testing%20Plan/penetration-testing/2.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/penetration-testing/2.png)

1. After the testing, the report will be uploaded to the **Artifacts**. It will be downloaded and reviewed to ensure the website's security and identify threats.

[![Performance Test image 3](Testing%20Plan/performance-testing/3.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/performance-testing/3.png)

- Penetration testing report [![Penetration Test image 3](Testing%20Plan/penetration-testing/3.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/penetration-testing/3.png) [![Penetration Test image 4](Testing%20Plan/penetration-testing/4.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/penetration-testing/4.png) [![Penetration Test image 5](Testing%20Plan/penetration-testing/5.png)](https://github.com/LangzeL/GD/blob/main/Testing Plan/penetration-testing/5.png)

### Documentation

- All tests should be documented with objectives, tools, methodologies, and results.
- The identified issues should be labelled, documented and prioritized for fixing.

------------

## Deployment

Update in 10th/Nov/2023, the overall LBP website  was not deploy by the membership group yet, therefore the deployment in this document was only for LBP content group, which is deploy by team006.
