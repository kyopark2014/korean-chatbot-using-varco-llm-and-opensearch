

3. EBS 크기 변경을 수행을 하기 위해서 스크립트를 다운로드 하여 수행합니다. 수행된 명령어는 EBS 용량을 80G로 변경합니다.

curl https://raw.githubusercontent.com/aws-samples/generative-ai-demo-using-amazon-sagemaker-jumpstart-kr/main/resize.sh -o resize.sh
chmod a+rx resize.sh && ./resize.sh 80

4. 소스를 다운로드합니다.

curl https://raw.githubusercontent.com/aws-samples/generative-ai-demo-using-amazon-sagemaker-jumpstart-kr/main/blogs/korean-chatbot-using-varco-llm-and-opensearch/korean-chatbot-using-varco-llm-and-opensearch.zip -o korean-chatbot-using-varco-llm-and-opensearch.zip && unzip korean-chatbot-using-varco-llm-and-opensearch.zip
