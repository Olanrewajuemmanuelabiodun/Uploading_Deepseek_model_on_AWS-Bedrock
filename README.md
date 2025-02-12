# Uploading the DeepSeek Model to AWS Bedrock

This repository provides a detailed guide on how to upload the DeepSeek model to Amazon Bedrock and run it.

### Steps to Upload the DeepSeek Model:

1. **Download the Distilled Model**:  
   Begin by downloading the DeepSeek distilled model with 8 billion parameters from Hugging Face.

2. **Create AWS Access Keys**:  
   Generate your AWS access keys, which are necessary for uploading the downloaded model files to an S3 bucket in Amazon.

3. **Upload the Model to Amazon S3**:  
   Once the access keys are set, upload the model files to your S3 bucket.

4. **Upload the Model to Amazon Bedrock**:  
   Navigate to Amazon Bedrock and upload the model. Please note that the upload process may take some time depending on the size of the model.

5. **Model Ready for Use**:  
   After the upload completes, the model will be ready to use on Amazon Bedrock.

6. **Import and Compare Models**:  
   You can also click on the “Import Model” option in Amazon Bedrock, where you can compare the responses from the DeepSeek model with those of other models available on the platform.

7. **Customizable Settings in Amazon Bedrock**:  
   In Amazon Bedrock, you can customize various settings such as temperature, top-k, and text length to fine-tune the model's performance.

### Running the Model on Google Colab (Optional):
If you prefer not to run the model on AWS, you can execute it on Google Colab by using the model ARN (Amazon Resource Name), which you can copy from AWS after the model upload is completed.
