# RevitGPT
## Overview

RevitGPT is a Revit plug-in that integrates OpenAI's GPT model to assist architects and engineers during the design process. This plug-in allows users to query building regulations, fire safety codes, and environmental guidelines directly from within Revit, using uploaded regulatory documents as a context for generating intelligent responses. 

 ## Features

* __Key Command:__ Securely input and store your OpenAI API key for session-long use.
* __Rag Command:__ Upload regulatory documents (e.g., building codes, safety standards) for context-aware AI interactions.
* __Chat Command:__ Access a responsive chat interface to ask targeted questions about your design or the uploaded documents.
* __Logging:__ Detailed logs of API interactions for error tracking and debugging.

## Use Cases

* __Graph Neural Networks (GNNs):__ Prepare AutoCAD drawing data for advanced machine learning tasks using GNNs.
* __Object Recognition:__ Enable object recognition and classification tasks by converting geometric entities into structured graph data.
* __Data Analysis:__ Facilitate spatial and relational analysis of drawing data in a graph-based framework.

## Installation
### Prerequisites

- **Revit**: Version 2017 or later.
- **.NET Framework**: Compatible with the Revit version in use (e.g., .NET Framework 4.8 for Revit 2017).
- **OpenAI API Key**: Ensure access to the GPT models relevant to your needs.
  
### Prerequisites



## Common Runtime Errors

**Negative Fiedler Value :** Results that are very close to zero but slightly negative are possible. This is due to the limitations of the floating-point precision. In this case assume the result as 0. 

## Usage with Commands

#### EXTRACTTOGRAPH      
-Function       : Extracts relevant data from the current drawing and saves it as a .json file.\
-Purpose        : The file can be used to train the model.



