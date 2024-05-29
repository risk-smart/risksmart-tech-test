# RiskSmart Tech Test

Please do not fork this repo, submit your application (excluding dependencies) in Zip file.

## British Geological Survey Sensors Plotter

### Introduction

The British Geological Survey (BGS) is a world-leading geological survey and global geoscience organisation, focused on public-good science for government and research to understand earth and environmental processes.

They are the UK’s premier provider of objective and authoritative geoscientific data, information and knowledge to help society to use its natural resources responsibly, manage environmental change and be resilient to environmental hazards.

### The task

BGS collects an processes a large amount of data from various sensors across the UK. Build a simple web application that presents the user with a list of Features of Interests. Each (well, most) Feature will have a list of observations associated with it. An observation is a piece of numerical data collected from one of the sensors located at the site. When a user selects a feature, display a dropdown list with all the sensors that have an observation for that features. When the user selects a sensor display the following observation details:

- Number of data points
- Min
- Max
- Mean

Note: not all sensors will have sufficient data, some might only have one entry point and the min, max and average will be the same. Don't worry. If you want you can also plot the results over time. Plotting _all_ data returned for a feature however yields a much more interesting graph.

![An example what the app might look like](Sample.png)

### Technical details

The BGS API docs can be accessed at [https://sensors-docs.bgs.ac.uk/](https://sensors-docs.bgs.ac.uk/). This is a free and open API, you don't need to authenticate but be mindful that if you make too many requests you could get rate-limited.

We use React and TypeScript at RiskSmart but that doesn't mean you have to. Use a language and framework that demonstrate your skills the best. We also don't expect you to build a fancy UI, keep it simple (we use [CloudScape Design System](https://cloudscape.design/), it also does charts).

For this test, we will be excluding all cloud and CI/CD aspects. We want you to show us what you're capable of, and we will not be marking the test against a set criteria. We want you to think, pivot, and be creative, just as we do every day.

### Considerations

- Volume, there's a lot of data being returned by the API
- Error handling, not every feature or sensor will have meaningful data
