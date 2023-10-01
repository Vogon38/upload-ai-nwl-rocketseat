# upload.ai

> Developed with 💜 during Rocketseat's Next Level Week

**upload.ai** is a project developed during Rocketseat's Next Level Week (NWL). This project aims to create a platform that allows users to upload videos and obtain transcriptions or additional information generated by an Artificial Intelligence (AI).

## Main Features

- Upload videos in MP4 format.
- Generation of transcriptions from videos.
- Selection of prompts to customize transcriptions.
- Selection of AI models for content generation.
- Control of AI "temperature" to adjust the creativity of text generation.

## Submodules

This project includes the following submodules:

### 1. `upload-ai-web`

This submodule contains the frontend code for the upload.ai platform.  
Check out the README.md to the front [here](https://github.com/Vogon38/upload-ai-web-nwl-rocketseat/blob/6a8753df9c4f0405c362b14e74b086e25d64dc55/README.md) 👌

### 2. `upload-ai-server`

This submodule contains the backend code for the upload.ai platform.  
Check out the README.md to the server [here](https://github.com/Vogon38/upload-ai-server-nwl-rocketseat/blob/d83679ea13e964e0ef5c06b4f6e04ca70dc0e325/README.md) 👌

## Getting Started

1. **Clone the Repository:**
   - Clone this repository to your local machine using the following command:
     ```
     git clone https://github.com/Vogon38/upload-ai-nwl-rocketseat.git
     ```

2. **Initialize Submodules:**
   - After cloning the main repository, navigate to its root directory:
     ```
     cd upload-ai-nwl-rocketseat
     ```
   - Initialize the submodules using the following command:
     ```
     git submodule init
     ```

3. **Update Submodules:**
   - To fetch the latest code for all submodules, run:
     ```
     git submodule update
     ```

4. **Working with Submodules:**
   - Each submodule is a separate Git repository. You can navigate to a submodule directory, make changes, commit them, and push to the submodule's repository independently.

5. **Updating Submodules in the Main Repository:**
   - To update the reference to a submodule in the main repository to a new version, navigate to the submodule directory, check out the desired branch or commit, and then commit the changes in the main repository.

## Important Notes

- Make sure to follow the above steps to initialize and update submodules after cloning the main repository.

- If you encounter any issues or need further assistance, please refer to the documentation of individual submodules or consult the maintainers of those repositories.

- Remember that submodules allow us to manage external dependencies more efficiently, but they also add complexity to the workflow. Be sure to commit submodule references in your main repository to record the submodule versions.

