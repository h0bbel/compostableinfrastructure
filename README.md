# HomeLab Reimagined


## Codename: Compostable Infrastructure
Named *Compostable Infrastructure* as my original tweet on the topic [had a typo](https://twitter.com/h0bbel/status/1413047607090352129) in it, and [Filip Verloy ran with it](https://twitter.com/filipv/status/1413048628684414978).

<img align="right" width="320" height="480" src="images/gabriel-jimenez-jin4W1HqgL4-unsplash.jpg">

## Executive Summary

The purpose of this document is to describe in necessary detail the current project description to represent a suitable model generating Conceptual, Logical and Physical designs for HomeLab.

The [Conceptual Design](Conceptual.md) presents the proposed structure of the datacenter transformation project, such as the requirements, assumptions and risks involved.

The [Logical Design](Logical.md) is based on the conceptual design, and provides a more detailed view of the components and relationships.

This in turn results in a [Physical Design](Physical.md) that can be used to build the entire stack of services.

The purpose of the lab is to provide infrastructure services as well as a training ground for various technologies.

## "Business" Background

*By developing the documentation in this manner, the idea is for it to work as an exercise in writing enterprise design documents.*

### Participants

The people listed in the following table provided key input into this design:

|Name|Role|
|---|---|
|Christian Mohn|Owner|

#### Version History

|Date|Revision|Author|Comments|
|---|---|---|---|
|08.08.2021|0.0.1|CM|Initial check in of project "Compostable Infrastructure"
|08.08.2021|0.0.2|CM|Add link to resources document, placeholders for Conceptual, Logical and Physical.
|08.08.2021|0.0.3|CM|Added some details to Physical.md (Hardware + VLANs)
|08.08.2021|0.0.4|CM|Fleshed out directory structure, added markdown_index_generator.rb and index.md
|08.08.2021|0.0.4|CM|Removed markdown_index_generator.rb, no need for it to be a part of the repo.