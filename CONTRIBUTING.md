# 🧑‍🍳 How to Add a Recipe
All recipes in this project are licensed under CC BY 4.0. 
We’re thrilled you want to contribute! Follow these steps:

 1. Fork the Repository
Click the Fork button at the top right of the repo.
💡 Note: Replace `YOUR-USERNAME` with your actual GitHub username in all commands.

 2. Clone Your Fork
```bash
git clone https://github.com/YOUR-USERNAME/collaborative-cookbook.git
cd collaborative-cookbook

3. Create a New Branch
bash
git checkout -b add-your-recipe-name
Example: git checkout -b add-masala-dosa 

4. Add Your Recipe File
4.1 Choose a category folder inside recipes/ (e.g., indian/, desserts/).
If your cuisine doesn’t exist, create a new folder:
bash
mkdir recipes/your-cuisine
4.2 Create your recipe file:
bash
touch recipes/indian/your-recipe.md
4.3 Use this format in your .md file:
# Recipe Title
- **Cuisine:** Indian
- **Author:** @your-github-username
- **Ingredients:**
  - Item 1
  - Item 2
- **Steps:**
  1. Step one
  2. Step two
- **Cooking Time:** 30 mins


5. (Optional) Update README.md
Add your recipe to the Recipe Index so others can find it:
- [Your Recipe Name](recipes/indian/your-recipe.md)
Place it under the correct cuisine section (e.g., ### Indian).

6. Commit and Push
git push origin add-your-recipe-name

7. Open a Pull Request
Go to your fork on GitHub.
Click Compare & pull request.
Submit your PR!
Done! Your recipe will be reviewed and added to the cookbook

Note : - 
3. `CODE_OF_CONDUCT.md`
Use the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/)