![sheaNET](https://github.com/user-attachments/assets/bd6a6128-7528-4308-b10d-a715fcd17f7a)
# sheaNET
sheaNET leverages Watsonx GenAI to promote sustainable alternatives to deforestation

- [Project summary](#project-summary)
  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
  - [How our technology solution can help](#how-our-technology-solution-can-help)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
  - [IBM watsonx product(s) used](#ibm-ai-services-used)
  - [Other IBM technology used](#other-ibm-technology-used)
  - [Solution architecture](#solution-architecture)
- [Presentation materials](#presentation-materials)
  - [Solution demo video](#solution-demo-video)
  - [Project development roadmap](#project-development-roadmap)
- [Additional details](#additional-details)
  - [How to run the project](#how-to-run-the-project)
  - [Live demo](#live-demo)
- [About this template](#about-this-template)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## Project summary
**sheaNET** leverages Watsonx PromptLab and Assistant to promote sustainable alternatives to deforestation.

### The issue we are hoping to solve
Communities in Northern Uganda rely on shea trees for charcoal production, leading to deforestation and environmental degradation. This issue worsens climate change and post conflict poverty, leaving women and youth with limited sustainable income sources.

### How our technology solution can help
**sheaNET** leverages *WatsonX AI* to promote sustainable alternatives to deforestation with AI-driven insights on sustainable shea-based products for post-conflict communities.

### Our idea
**sheaNET** is an innovative platform designed to empower rural communities, particularly women and youth, in Northern Uganda by leveraging teh capabilities of WatsonX GenAI and Watsonx Assistant to promote sustainable alternatives to deforestation. The primary focus of sheaNET is to provide these communities with knowledge and tools to shift from unsustainable practices like charcoal production, which leads to deforestation, to regenerative  and climate-friendly uses of shea trees, such as producing marketable shea-based products. These products, including shea butter, lotions, soaps, and cosmetics, offer a viable alternative for income generation, enhancing environmental sustainability and economic resilience.
The problem context is that, the Northern region of Uganda is characterized by high levels of poverty, particularly among post-conflict populations, many of whom rely on  unsustainable practices like deforestation to survive. The mass cutting of trees, particularly shea tree, for charcoal production not only depletes natural resources but also exacerbates the regions's vulnerability to climate change. Deforestation has led to prolonged droughts, soil erosion, and reduced agricultural productivity, further entrenching poverty and hunger in the region.
At the same time, the shea tree offers a unique economic opportunity. Its seeds produce shea butter, which is in high demand in the global beauty and skincare industries. however, due to lack of awareness, resources, and access to markets, most people in these communities continue to exploit shea trees for charcoal instead of harnessing their potential for higher-value, sustainable products.
sheaNET tackles these issues by using WatsonX Prompt Lab to generate actionable insights and new knowledge on sustainable practices for shea tree cultivation and product development. The platform integrates IBM's cutting-edge AI technology to provide communities with the necessary information to repurpose shea trees from charcoal production into higher-value markets. Through Watsonx Assistant, users can interact with the system in their native languages, making the solution accessible and culturally relevant.
The Watsonx Prompt Lab pulls from avariety of data sources, including local knowledge from WORUDET (Women and Rural Development Networks), market data, and environmental studies, to offer tailored solutions to each user. The Ai provides recommendations on sustainable harvesting techniques, agroforestry practices, and business models for producing shea-based products. Additionally, it connects users with training modules on product formulation, packaging, and marketing, enabling them to enter local and global markets.

## Technology implementation
1. User Interaction: Women and youth access sheaNET through mobile phones or computers, interacting with a Watson Assistant via the WORUDET website (https://worudet.net/sheanet/). They ask questions about alternative livelihoods, sustainable practices, or product development, and receive real-time guidance from the platform.
2. Watsonx AI Prompt Lab Output through Assistant: Using Watsonx Assistant, the platform generates relevant and personalized information. Forexample, it can suggest best practices for shea-based products, and provide insight into market trends.
3. Access to Markets: sheaNET shall help connect users with market opportunities, offering insights on how to package, brand, and sell shea-based products both locally and internationally. The platform provides recommendation on entering value chains that offer higher economic returns than charcoal production.

### IBM watsonx product(s) used
**Featured watsonx products**

- [watsonx.ai](https://www.ibm.com/products/watsonx-ai) - sheaNET uses Watsonx Prompt Lab by creating a sandbox where guadrails are placed to control output and greedy sampling option selected to improve creativity. The values of temperature, Top P and Top K are fine tuned to ensure an optimal output and few token numbers are set to increase precision and shorter interpretable and graspable sentences.
- [watsonx Assistant](https://cloud.ibm.com/catalog/services/watsonx-assistant) - Our chatbot is created using Watsonx Assistant intergating the model from Prompt Lab while fine tuning a converstaional response. We are also modelling it to integrate our pre-loaded files from Women and Rural Development Networks about existing opportunities for women and youths subscribed to WORUDET through sheaNET.

### Other IBM technology used
**Additional IBM AI services (Remove any that you did not use)**

- [Watson Studio](https://cloud.ibm.com/catalog/services/watson-studio) - WHERE AND HOW THIS IS USED IN OUR SOLUTION

- [Natural Language Understanding](https://cloud.ibm.com/catalog/services/natural-language-understanding) - WHERE AND HOW THIS IS USED IN OUR SOLUTION

- [Language Translator](https://cloud.ibm.com/catalog/services/language-translator) - WHERE AND HOW THIS IS USED IN OUR SOLUTION

### Solution architecture

REPLACE THIS EXAMPLE WITH YOUR OWN, OR REMOVE THIS EXAMPLE

Diagram and step-by-step description of the flow of our solution:

![Video transcription/translaftion app](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png)

1. The user navigates to the site and uploads a video file.
2. Watson Speech to Text processes the audio and extracts the text.
3. Watson Translation (optionally) can translate the text to the desired language.
4. The app stores the translated text as a document within Object Storage.

## Presentation materials

_INSTRUCTIONS: The following deliverables should be officially posted to your My Team > Submissions section of the [Call for Code Global Challenge resources site](https://cfc-prod.skillsnetwork.site/), but you can also include them here for completeness. Replace the examples seen here with your own deliverable links._

### Solution demo video

[![Watch the video]![![sheaNET](https://github.com/user-attachments/assets/9d0e55ef-5c11-493e-8441-366803548f4b)
](https://youtu.be/tmsDPcwRvqw)

### Project development roadmap

The project currently does the following things.

- Feature 1
- Feature 2
- Feature 3

In the future we plan to...

See below for our proposed schedule on next steps after Call for Code 2024 submission.
![sheaNET Project Roadmap](https://github.com/user-attachments/assets/73e1f63a-109b-4461-beb8-834338873979)

## Additional details
By encouraging regenerative uses of shea trees, sheaNET contributes to reducing of ecosystems in Northern Uganda. The platform promotes agroforestry practices, where shea trees are preserved and farmed alognside other crops, improving soil quality and reducing climate risks.
There to say, sheaNET aims to uplift post-conflict communities by providing a sustainable alternative to environmentally destructive practices. With the help of Watsonx Generative AI platforms and Watson Assistant, it equips these communities with knowledge and skills needed to create marketable products from shea trees, opening up new economic opportunities and contributing to the fight against climate change.

### How to run the project
The project can be run by accessing sheaNET through the WORUDET website here. https://worudet.net/sheanet/

### Live demo

You can test our solution by running it on your computer through this link. https://worudet.net/sheanet/


## About this template

### Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

### Authors

- **Aaron Masuba** - _Initial work_ - [AaronMasuba-Dev](https://github.com/aaronmasuba-dev)

### License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).
