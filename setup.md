1. conda create --name nvkmchat python=3.10
2. conda activate nvkmchat
3. pip3 install -r requirements.txt
4. create .env file with openai api
5. streamlit run src/app.py
6. to delete the envrionment --> conda remove --name nvkmchat --all


Delete git to restart 
sudo rm -r .git    

New SSH setup 


New GIT Setup 
echo "# nvkmchat" >> README.md
git init
git add README.md
git config --local user.name "Subhra"
git config --local user.email "b206423@gmail.com"
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:B206423/nvkmchat.git
git push -u origin main