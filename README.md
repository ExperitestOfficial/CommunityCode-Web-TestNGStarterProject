# CommunityCode Web: TestNG Starter Project
The TestNG Starter Project enables you to quickly run tests with minimal coding. The project itself compiles and can be run immediately.
## Setting Up the Project

To set up the project:
1. Clone the project by running the following:
   ```
   git clone https://github.com/ExperitestOfficial/CommunityCode-Web-TestNGStarterProject
   cd CommunityCode-Web-TestNGStarterProject
   ```   
1. Set up authentication by updating the following parameters in [cloud.properties](cloud.properties):
    * cloud.url - URL for the cloud the test runs in. For example, https://company.experitest.com/
    * cloud.accessKey -  Personal authentication. See [Obtaining Access Key](https://docs.digital.ai/bundle/TE/page/obtaining_access_key.html) to learn how to obtain an access key.

## Running Tests

To run the tests in this project, run the following on the command line:

```bash
./gradlew test
```

## Desired Capabilities
In this example we use desired capabilities to run a test on Chrome. Change the browser name in the capabilities to run you test on different browsers.

```
dc.setCapability(CapabilityType.BROWSER_NAME, "chrome");
```

Continuous Cloud Testing expands Selenium's capabilities and allows better control over your test.

See [Capabilities In Selenium Tests](https://docs.digital.ai/bundle/TE/page/capabilities_in_selenium_tests.html) to learn how to customize the desired capabilities for your tests.

## Documentation
To find out more about Continuous Cloud Testing usage, features, and best practices, visit our online [documentation](https://docs.digital.ai/bundle/TE/page/test_execution_home.html).

## Support
If you encounter an issue that is not covered here or in our online documentation, contact us at [support@digital.ai](mailto:support@digital.ai).