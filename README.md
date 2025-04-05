# API Migration Testing Tools

## Alternatives

- Hoppscotch (AKA Postwoman) - https://hoppscotch.io/ | https://postwoman.io/
- Postman - https://www.postman.com/
- Bruno - https://www.usebruno.com/
- Insomnia - https://insomnia.rest/
- SoapUI -  https://www.soapui.org/
- Thunder Client - https://www.thunderclient.com/
- Etc ...

## Sumary

| Feature                | Hoppscotch         | Postman            | Bruno              |
| ---                    | :---:              | :---:              | :---:              |
| Open Source            | :white_check_mark: | :x:                | :white_check_mark: |
| Web App - PWA          | :white_check_mark: | :white_check_mark: | :x:                |
| Desktop App            | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| VS Code Extension      | :x:                | :white_check_mark: | :white_check_mark: |
| Command Line Interface | :white_check_mark: | :white_check_mark: | :white_check_mark: | 
| Test Snippets          | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| AI Test Generator      | :x:                | :white_check_mark: | :x:                |
| Load Testing           | :white_check_mark: | :white_check_mark: | :x:                |
| Git Friendly           | :x:                | :x:                | :white_check_mark: |

## Hoppscotch (AKA Postwoman)

#### References 

- https://hoppscotch.io/
- Price & Docs
    - [Pricing](https://hoppscotch.com/pricing)
    - [Getting Started](https://docs.hoppscotch.io/documentation/getting-started/introduction)
- Downloads & Install
    - [Download Desktop App](https://hoppscotch.com/download)
    - [Install Hoppscotch CLI](https://docs.hoppscotch.io/documentation/clients/cli/overview)
- (Gary) Docker Hoppscotch CLI
    - https://github.com/Gary-Ascuy/hoppscotch-cli-docker
    - https://hub.docker.com/r/garyascuy/hoppscotch-cli
- (Gary) feat: add support for toBeDeepEqual in test scripts 
    - https://github.com/Gary-Ascuy/hoppscotch/pull/1

## Postman

#### References 

- https://www.postman.com/
- Price & Docs
    - [Pricing](https://www.postman.com/buy)
    - [Getting Started](https://learning.postman.com/docs/getting-started/overview/)
- Downloads & Install
    - [Download Desktop App](https://www.postman.com/downloads/)
    - [Install Postman CLI](https://learning.postman.com/docs/postman-cli/postman-cli-installation/)
    - [Not Recommended] [Install Newman CLI](https://www.npmjs.com/package/newman)
    - [Not Recommended] [VS Code Plugin](https://marketplace.visualstudio.com/items?itemName=Postman.postman-for-vscode)

## Bruno 

#### References 

- https://www.usebruno.com 
- Price & Docs
    - [Pricing](https://www.usebruno.com/pricing)
    - [Getting Started](https://docs.usebruno.com/introduction/what-is-bruno)
- Downloads & Install
    - [Download Desktop App](https://www.usebruno.com/downloads)
    - [Install Postman CLI](https://www.npmjs.com/package/@usebruno/cli)

## Conclusion (According to Gemini)

Postman and Hoppscotch are both API testing tools, but they cater to different needs: Postman is a robust, feature-rich platform with strong integrations and collaboration capabilities, while Hoppscotch is a lightweight, open-source, and self-hostable option focusing on simplicity and ease of use. 

### Postman

#### Strengths

- Feature-rich: Offers extensive functionality, including automated testing, integrations with various tools (GitHub, Jira, Slack), and collaboration features. 
- Scalable: Designed for larger teams and complex API testing needs. 
- Multiple Protocol Support: Supports REST, SOAP, GraphQL, and WebSocket protocols. 
- Community Support: Has a large and active community, providing ample resources and support. 

#### Weaknesses

- Learning Curve: The extensive features can lead to a steeper learning curve for new users. 
- Cloud Dependency: Requires an internet connection even for testing local APIs. 
- Cost: The free plan has limitations, and paid plans are required for more advanced features and team collaboration. 
- CPU Intensive: Can be heavy on CPU resources. 

### Hoppscotch

#### Strengths

- Lightweight and Fast: Designed for quick and simple API testing, with a focus on ease of use. 
- Open-Source and Self-Hostable: Offers flexibility and control over data storage and deployment. 
- Simplicity: Features a minimalistic interface, making it easy to learn and use. 
- Web-Based: Accessible from any browser, eliminating the need for desktop installations. 
- Free and Open Source: No cost to use, and source code is open and auditable. 

#### Weaknesses

- Limited Features: Offers fewer advanced features compared to Postman. 
- Smaller Community: The community is smaller than Postman's, potentially leading to less readily available support. 
- Less Integrations: Has fewer integrations with other tools and workflows compared to Postman. 


### Key Differences Summarized


| Feature | Postman | Hoppscotch |
| --- | --- | --- |
| Focus | Robust, feature-rich, enterprise-focused | Lightweight, simple, developer-focused |
| Complexity | High | Low |
| Learning Curve | Steeper | Easier |
| Features | Extensive | Limited |
| Integrations | Strong | Limited |
| Cost | Paid plans for advanced features | Free and Open Source |
| Self-Hostable | No | Yes |
| Data Storage | Cloud-based | Local or Cloud-based (choice) |

### Source

- https://dev.to/hoppscotch/hoppscotch-vs-postman-why-choose-hoppscotch-14km

## Versions

- HOPPSCOTCH Desktop
    - Version 25.3.0 (20250328.142950)
- HOPPSCOTCH CLI
    - `hopp --ver` - 0.20.3
- POSTMAN Desktop
    - Version 11.38.7
    - UI Version: 11.38.7-ui-250328-1229
    - Desktop Platform Version: 11.38.5 (11.38.5)
- POSTMAN CLI 
    - `postman --version` - 1.13.1
