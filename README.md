# Dolly
git project - challenging level
link to Notion: https://www.notion.so/Git-project-Dolly-130f96cc224a8069b97ede8e21a7672e
link to Hyperskills: https://hyperskill.org/projects/312?track=48

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c80fda68-3771-4473-9753-bfe0ad798de2/5142a646-a4fb-49ee-afc4-c0fc2a39105d/image.png)

git clone file:///tmp/dolly

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c80fda68-3771-4473-9753-bfe0ad798de2/ae64eec1-41b0-4424-9fcf-ba611ce1da10/image.png)

cd dolly
ls

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c80fda68-3771-4473-9753-bfe0ad798de2/2b85cfbb-9695-40a0-9383-3f08e3636ff1/image.png)

git checkout -b dev-mul
git branch

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c80fda68-3771-4473-9753-bfe0ad798de2/6a0cd281-f316-43c4-8652-7d3aaddcf59d/image.png)

cat [main.py](http://main.py/)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c80fda68-3771-4473-9753-bfe0ad798de2/b8b1106f-d017-4bfd-948b-ddf70359bfb1/image.png)

cd dolly
echo -e "def mul(num1, num2):
return num1 * num2" >> [main.py](http://main.py/)
cat [main.py](http://main.py/)
git status

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c80fda68-3771-4473-9753-bfe0ad798de2/4356c831-de9b-42ad-8ffa-2e0de0b27418/image.png)

git add [main.py](http://main.py/)
git commit -m "New function multiplication"

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c80fda68-3771-4473-9753-bfe0ad798de2/b577c2bb-874e-4824-a8e6-a24fc1f07b04/image.png)

git checkout main
git merge dev-mul
git branch -d dev-mul

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c80fda68-3771-4473-9753-bfe0ad798de2/89c91526-4772-4e56-bdee-5400149d2d53/image.png)

git diff HEAD~
git push origin main
