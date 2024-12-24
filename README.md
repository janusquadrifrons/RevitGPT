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
  
### Steps

1. Download the provided `.dll` and `.addin` files.
2. Copy the `.dll` and `.addin` files to the Revit Add-ins folder:
   - Default path: `C:\ProgramData\Autodesk\Revit\Addins\<RevitVersion>`
3. Launch Revit and confirm the presence of the `RevitGPT` tab in the ribbon.

---

## Usage
### Key Command
1. Select the **Key** button within the `RevitGPT` tab.
2. Input your OpenAI API key and confirm by clicking **Save**.

### Rag Command
1. Select the **Rag** button within the `RevitGPT` tab.
2. Choose a regulatory document (PDF or TXT, up to 10 MB) from the file dialog.
3. Verify that the file upload completes successfully.

### Chat Command
1. Select the **Chat** button within the `RevitGPT` tab.
2. Utilize the chat interface to pose queries about your design or the uploaded regulatory documents.
3. View AI-generated responses within the chat display area.

---

## Troubleshooting
### Common Issues
1. **API Key Missing:**
   - Ensure the key is entered via the **Key** command.
2. **Quota Errors:**
   - Verify sufficient quota availability on your OpenAI API dashboard. Remember, your API account should be filled separately from your ChatGPT subscription.

---

## Contributions
Contributions are encouraged! Follow these steps to contribute:
1. Fork the repository.
2. Create a new feature branch:
   ```bash
   git checkout -b feature/your-feature

