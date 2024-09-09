---
title: "Open AT Resources"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/NSS_MMC_Logo_Transparent.png # image is 1280x400px. the height is a bit too tall so I just pushed the text/images down in Canva.
  actions:
    - label: "Download All Open AT Resources"
      url: "https://github.com/makersmakingchange/OpenAT-Resources/archive/refs/heads/main.zip" # direct link to download the Main branch
excerpt: |
  Version 0.1 / Released September 2024

  - This website hosts resources to help designers create open source assistive devices.


feature_row:
  - image_path: assets/images/3D_Print_Banner.jpg
    alt: "Cartoon showing a ball on the screen of a tablet, with a hand moving the ball to a 3D printer on the left." 
    title: "3D Printing Resources"
    excerpt: "A resource outlining how to get started with 3D printing. The resource links to other tutorials and pages, and gives people an idea of where to start looking when first learning about 3D printing."
    url: "/_pages/3D_Printing/"
    btn_label: "Go to 3D Printing Resources"
    btn_class: "btn--primary"
  - image_path: assets/images/Arduino_Logo.jpg
    alt: "The Arduino Logo: the infinity loop with a minus sign in the left loop and a plus sign in the right loop, and Arduino written below." 
    title: "Arduino Resources"
    excerpt: "A resource outlining how to get started using Arduino. The resource links to other tutorials and pages, and gives people an idea of where to start looking when first learning about using Arduino."
    url: "/_pages/Arduino/"
    btn_label: "Go to Arduino Resources"
    btn_class: "btn--primary"
  - image_path: assets/images/CAD_Model.png
    alt: "Screenshot of a generic CAD model."
    title: "CAD Resources"
    excerpt: "A resource outlining how to get started designing with CAD. The resource links to other tutorials and pages, and gives people an idea of where to start looking when first learning about using CAD to create new devices."
    url: "/_pages/CAD/" 
    btn_label: "Go to CAD Resources"
    btn_class: "btn--primary"
  - image_path: assets/images/Stock_Parts_BOM_Header.PNG
    alt: "Screenshot of the header from the Stock Parts spreadsheet"
    title: "Commonly Used Parts"
    excerpt: "Many parts are used across multipled devices at MMC. The most common parts are listed here in the format of our Bill of Material (BOM) template to make it easy for designers to copy and paste relevant information into new BOMs."
    url: "/_pages/Common_Parts/"
    btn_label: "Go to Commonly Used Parts"
    btn_class: "btn--primary"
  - image_path: assets/images/NSS_MMC_Logo_Transparent.png
    alt: "The Makers Making Change and Neil Squire Society logos."
    title: "Documentation Templates"
    excerpt: "Looking to design a new device and want to use the documentation templates we use? Grab them here!"
    url: "/_pages/Documentation_Templates/" 
    btn_label: "Go to Documentation Templates"
    btn_class: "btn--primary"
  - image_path: assets/images/GitHub_Logo.png
    alt: "Screenshot of the GitHub Logo."
    title: "Using GitHub"
    excerpt: "New to GitHub? These resources can help introduce you to how to navigate using GitHub."
    url: "/_pages/Git_Hub/"
    btn_label: "Go to GitHub Resource"
    btn_class: "btn--primary"
  - image_path: assets/images/NSS_MMC_Logo_Transparent.png
    alt: "The Makers Making Change and Neil Squire Society logos."
    title: "Open Source Licenses"
    excerpt: "Designing an open-source device and not sure which license to apply? While we can't give you specific advice, we have summarized some information on different types of open-source licenses."
    url: "/_pages/Licenses/" 
    btn_label: "Go to Open-Source License Resource"
    btn_class: "btn--primary"
  - image_path: assets/images/PCB_Header.jpeg
    alt: "Closeup image of a printed circuit board (PCB)."
    title: "Designing Printed Circuit Boads (PCBs)"
    excerpt: "This resource is under development."
    url: "/_pages/PCB_Design/"
    btn_label: "Go to PCB Design Resources"
    btn_class: "btn--primary"
  - image_path: assets/images/Example_Part.png
    alt: "A closeup of a 3D printed part."
    title: "Photo and Video Resources"
    excerpt: "Taking photos while designing a new device, or creating videos about your device? These resources can help you make sure the images and videos meet your goals for them."
    url: "/_pages/Photos_and_Videos/" 
    btn_label: "Go to Photo and Video Resources"
    btn_class: "btn--primary"
feature_row2:
  - image_path: assets/images/home/gaming-at.png
    alt: "Various assistive switches in a box resting on red crinkle packing paper" # complete this once image is fixed.
    title: "Low Cost Assistive Tech"
    excerpt: 'Visit the Makers Making Change library and request a device or find the files to build one.'
    url: "https://www.makersmakingchange.com/s/category/assistive-devices/0ZGJR00000002Mn4AI?c__results_layout_state=%7B%7D"
    btn_label: "Find Low Cost AT"
    btn_class: "btn--primary"
feature_row3:
  - image_path: assets/images/home/sign-up.png
    alt: "A close up shot of someones hand using a pen and MMC Signature Guide device to sign up on a page."
    title: "Want to stay up to date on Makers Making Change?"
    excerpt: 'Sign up for the Makers Making Change website! Find 200+ open source low cost assitive technologies, resources, and upcoming events.'
    url: "https://www.makersmakingchange.com/s/login/SelfRegister?startURL=%2Fs%2F%3Ft%3D1706554861397"
    btn_label: "Sign up to Makers Making Change"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}
