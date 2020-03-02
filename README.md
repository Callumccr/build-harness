<!-- 














  ** DO NOT EDIT THIS FILE
  ** 
  ** This file was automatically generated by the `build-harness`. 
  ** 1) Make all changes to `README.yaml` 
  ** 2) Run `make init` (you only need to do this once)
  ** 3) Run`make readme` to rebuild this file. 
  **
  ** (We maintain HUNDREDS of open source projects. This is how we maintain our sanity.)
  **















  -->

#

[![README Header][logo]][website]

# build-harness

## Module description


The `build-harness` project is to provide a centralised repository to facilitate building documentation, Dockerfiles, Helm charts, and more.

It's designed to work with any CI/CD




Project: **[%!s(<nil>)](%!s(<nil>))** : [[%!s(<nil>)](%!s(<nil>))] | [[%!s(<nil>)](%!s(<nil>))] 







## Usage


In your root repository of the codebase, at the top of your `Makefile` add, the following...
  ```make
  include $(shell rm -rf *build-harness)$(shell git clone "https://github.com/Callumccr/build-harness.git")
  ```
This will download a `Makefile` called `.build-harness` and include it at run-time. We recommend adding the `.build-harness` file to your `.gitignore`.
This automatically exposes many new targets that you can leverage throughout your build & CI/CD process.

One you've pulled down `build-harness`, you can run a series of make commands to perform various actions









## Related Projects

You can find more [Terraform Modules](terraform_modules) by vising the link.

Additionally, check out these other related, and maintained projects.

- [%!s(<nil>)](%!s(<nil>)) - %!s(<nil>)



## References

For additional context, refer to some of these links. 

- [cloudposse/build-harness](https://github.com/cloudposse/build-harness) - Unmodified upstream provided for this module
- [Wikipedia - Test Harness](https://en.wikipedia.org/wiki/Test_harness) - The `build-harness` is similar in concept to a "Test Harness"



## Help

**Got a question?** We got answers. 

File a Github [issue](https://github.com/Callumccr/build-harness/issues), or message us on [Slack][slack]


### Contributors

|  [![Callum Robertson][callumccr_avatar]][callumccr_homepage]<br/>[Callum Robertson][callumccr_homepage] |
|---|


  [callumccr_homepage]: https://www.linkedin.com/in/callum-robertson-1a55b6110/
<<<<<<< HEAD
  [callumccr_avatar]: https://media-exp1.licdn.com/dms/image/C5603AQHb_3oZMZA5YA/profile-displayphoto-shrink_200_200/0?e=1588809600&v=beta&t=5QQQAlHrm1od5fQNZwdjOtbZWvsGcgNBqFRhZWgnPx4

=======

  [callumccr_avatar]: https://wariva-github-assets.s3.eu-west-2.amazonaws.com/callum.jpeg




---
>>>>>>> master



---


[![README Footer][logo]][website]

  [logo]: https://wariva-github-assets.s3.eu-west-2.amazonaws.com/logo.png
  [website]: https://www.linkedin.com/company/52152765/admin/
  [github]: https://github.com/Callumccr
  [slack]: https://wariva.slack.com
  [linkedin]: https://www.linkedin.com/in/callum-robertson-1a55b6110/
  [terraform_modules]: https://github.com/Callumccr