### AMP
[AMP](https://amp.dev/) is an open-source HTML framework supported by Google, enabling you to offer a consistently fast experience across all devices and platforms. It offers loads of components which let you overcome many disadvantages of static websites like the ability to get a dynamic search without writting any custom JavaScript and maybe most importantly it favors AMP Pages in its [Rich Search Results](https://developers.google.com/search/docs/guides/about-amp).

### Travis CI
[Travis CI](https://travis-ci.org/) is a hosted continuous integration service, which is free to use with GitHub open-source repositories. We'll use it to test our code in the **staging environment** and deploy the live website into **production**. That actually means that we are able make changes directly on the [GitHub](https://github.com) website and it's published through Travis CI without having and development environment available. This is clearly not a good way to do complex things, but good enough to fix a typo or such when you are on the go. 