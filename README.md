# RiskSmart Tech Test

Please do not fork this repo, submit your application (excluding dependencies) in a Zip file.

## British Geological Survey Sensors Plotter

### Introduction

The British Geological Survey (BGS) is a world-leading geological survey and global geoscience organisation, focused on public-good science for government and research to understand earth and environmental processes.

They are the UK’s premier provider of objective and authoritative geoscientific data, information and knowledge to help society to use its natural resources responsibly, manage environmental change and be resilient to environmental hazards.

### The task

BGS collects an processes a large amount of data from various sensors across the UK. Build a simple web application that presents the user with a list of Features of Interests. Once a feature has been selected display a secondary list with a list of datastreams associated with the selected feature. When the user selects one of the available datasets, calculate and display the following details:

- Number of data points
- Min
- Max
- Mean

If you can, plot the datapoints on a chart. Make sure to use a sensible time window, there's a lot of data.

![An example what the app might look like](Sample.png)

### Technical details

The BGS API docs can be accessed at [https://sensors-docs.bgs.ac.uk/](https://sensors-docs.bgs.ac.uk/). This is a free and open API, you don't need to authenticate but be mindful that if you make too many requests you could get rate-limited.

We use React and TypeScript at RiskSmart but that doesn't mean you have to. Use a language and framework that demonstrate your skills the best. We also don't expect you to build a fancy UI, keep it simple (we use [CloudScape Design System](https://cloudscape.design/), it also does charts).

For this test, we will be excluding all cloud and CI/CD aspects. We want you to show us what you're capable of, and we will not be marking the test against a set criteria. We want you to think, pivot, and be creative, just as we do every day.

### Considerations

- Volume, there's a lot of data being returned by the API
- Error handling, not every feature will have meaningful data

