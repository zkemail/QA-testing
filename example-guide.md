Hi, ZK Email team here, in this doc we are going to highlight the right way to organize, convey and submit the QA testing feedbacks. 

We have a pretty detailed checklist for the steps and user actions you need to perform in order to complete the QA test.  

[Email Wallet QA Guide](https://www.notion.so/Email-Wallet-QA-Guide-107173f6187940a8aa53591adeae00f4?pvs=21)

We recommend you to copy paste the checklist in your personal doc, this makes sure you don't miss any one of them.

*Note - Although, we tried to include most of the important and essentials steps, please feel free to add any other steps that you think is missing; or convey to us directly if are stuck at a step or cannot find a particular step in the flow.*

## Example submission doc

To-dos

> 💡 ### Mark as "Completed" as you go through them

[To Do](https://www.notion.so/ababcc2c94824f768ac98e82c462ece5?pvs=21)

### Browsers

- [x] Chrome
- [x] Safari
- [x] Arc
- [ ] Firefox
- [ ] Brave

### OS

- [x] Windows
- [ ] Mac
- [ ] Linux
- [ ] Chromebook

## Setup Details #1

**Date tested - 19 January 2025**

**OS** - Windows

> 💡 ### Be as specific as possible
>
> Please don't be vague in your responses. Here, using Windows as OS doesn't provide as much context. Use Windows 11/10 or whatever version you are using.

**Browser** - Brave

**Device** - Windows laptop connected to a 32 inch monitor(only monitor screen being used)

**Display Details**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/7e5ce7c7-888d-4853-a5a3-76ff0c68bcdb/64057fec-a1b2-4499-aa60-290ab367f4f3/image.png)

> 💡 ### Display Details
>
> Frontend performance and rendering is dependent upon the display size. We recommend you to share the display details so as to help us better understand what your current active screen is.

## QA Testing

### 1. Issue - The footer is not bottom aligned with respect to the screen(frontend)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/7e5ce7c7-888d-4853-a5a3-76ff0c68bcdb/ee8eb83a-b2f4-4f50-a101-da22106b84cd/image.png)

> ✅ ### This is the first right step to submitting an issue
>
> Submit complete screenshot with console open on the side and the Browser icon visible in the tab bar below. (In the case of mobile devices the bottom tab and the console won't be visible, so ignore in that case)

The footer is weirdly placed in the center of the screen

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/7e5ce7c7-888d-4853-a5a3-76ff0c68bcdb/4cb6aedc-9d2b-4ee6-9f38-342424a13b5f/image.png)

> ✅ ### Second step
>
> If there is a problem in a part of a UI we also recommend you to put an individual image of that UI. It helps us to pin point the problem and set in the context

### 2. Issue - Images by default are hidden - says it's a spam(email template)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/7e5ce7c7-888d-4853-a5a3-76ff0c68bcdb/a36fd85a-e7d2-4275-aecf-8cfd498586b7/image.png)

> ✅ ### When sharing a complete screen is not a good idea
>
> If you are using a mail client it's better to just post the image of the email. This way you can keep your personal space private.

> ⛔ ### Complete context not provided
>
> There is an obvious problem, in the above issue reported, it doesn't specify the email client been used(Gmail/Hotmail/Apple Mail)

## Setup Details #2

**Date tested - 19 January 2025**

**OS** - Windows 11

**Browser** - Chrome

**Device** - Windows laptop connected to a 32 inch monitor(only monitor screen being used)

**Display Details**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/7e5ce7c7-888d-4853-a5a3-76ff0c68bcdb/64057fec-a1b2-4499-aa60-290ab367f4f3/image.png)

> ✅ ### Distribute issues into different Setups
>
> Please distribute issues into different setups. Setup changes can be as minute as the above mentioned example where only the Browser changed from the Arc to Chrome

### 3. Issue - Test dropdown has the contrast issue(frontend)

> ✅ ### Continue the numbering of issue in case of setup changes

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/7e5ce7c7-888d-4853-a5a3-76ff0c68bcdb/7baa2640-46bf-4bea-b368-93a79013d71a/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/7e5ce7c7-888d-4853-a5a3-76ff0c68bcdb/bdac952a-5d43-45c9-9f8a-b4b404f64e5c/image.png)