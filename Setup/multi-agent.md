conda create --name multi-agent-3.12 python=3.12

conda activate multi-agent-3.12

conda install jupyter scikit-learn numpy pandas matplotlib ipympl openai transformers 

pip install crewai==0.28.8 crewai_tools==0.1.6 langchain_community==0.0.29 --user

conda deactivate multi-agent-3.12
