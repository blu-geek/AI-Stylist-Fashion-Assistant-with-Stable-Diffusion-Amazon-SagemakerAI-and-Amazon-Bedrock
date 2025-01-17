
# Creating Personalized Outfit Recommendations with Amazon Bedrock, Sagemaker and Stable Diffusion

As a Generative AI Engineer at Valtara, you are tasked with enhancing your company's customer service automation by integrating advanced AI models. Your current project involves using Amazon Bedrock's Titan model via SageMaker Studio to generate personalized outfit recommendations for clients. The objective is to create a system that produces visually appealing and contextually appropriate outfit suggestions using Stable Diffusion, improving customer satisfaction

# Architecture

<img width="718" alt="Screenshot 2025-01-17 at 10 43 56" src="https://github.com/user-attachments/assets/cd76fc11-e827-41ab-88ac-4fa74e5e508e" />


# Activity Guide: AI Stylist - Creating Personalized Outfit Recommendations Using Amazon Bedrock, SageMaker, and Stable Diffusion

1. Set Up SageMaker Studio Environment (AWS SageMaker Studio)
   
- Launch SageMaker Studio:
Open Amazon SageMaker Studio, navigate to the JupyterLab interface, and open a terminal.
- Prepare Environment:
Ensure your SageMaker Studio environment is properly configured.
Necessary dependencies and configurations will be included in the code provided in the repository.

2. Install Dependencies (Jupyter Notebook)

- Open the Notebook:
Use the provided code to set up the environment in SageMaker Studio.
- Run Setup Cells:
Sequentially execute setup cells to install the required Python libraries.
Validate that all dependencies are installed correctly.

3. Generate Outfit Recommendations (Amazon Bedrock, SageMaker)

- Input Prompts:
Use Amazon Bedrock with the Titan model to craft text-based prompts for generating outfit suggestions.
Example Prompt:
Generate a casual summer outfit suggestion for a male, age 25-35.
- Text Output Generation:
Execute code cells to pass the prompts to Bedrock and retrieve the outfit suggestions.
- Generate Images (Stable Diffusion):
Use Stable Diffusion to convert the text outputs into visually appealing outfit images.

4. Test and Evaluate Results

- Validate Outputs:
Check that the generated outfits meet the criteria provided in the input prompts.
- Save Results:
Store generated text and images in an Amazon S3 bucket for later analysis and sharing.
- Share Your Learnings

5. Clean Up Resources

- Stop Jupyter Notebook (Amazon SageMaker):
Go to SageMaker Studio, stop the running Jupyter notebook, and delete the associated environment.
- Delete S3 Bucket (Amazon S3):
Empty and delete the bucket used for storing generated text and images.
- Terminate Domain (Amazon SageMaker):
Remove the SageMaker domain and associated users.

6. Troubleshooting

- Issue: Dependency Errors:
Rerun setup cells in the notebook or refer to error logs for missing dependencies.
- Issue: Model Deployment Issues:
Confirm that the Stable Diffusion model is deployed in the same region as SageMaker Studio.
- Issue: Performance Delays:
Upgrade to a more powerful SageMaker instance (e.g., ml.p3.2xlarge) for faster processing.

7. Summary

Leveraged Amazon Bedrock and Stable Diffusion to create personalized outfit recommendations.
Integrated text and image generation for real-world applications in the AI Stylist use case.

# Note: The complete code for this activity guide is available in the repository for further reference and execution.
