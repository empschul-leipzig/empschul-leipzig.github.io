# Making changes to the content

* Fetch any upstream changes to your local repo. 

* Edit the Markdown .md files. When you push changes to the remote repo, Github will build the site.

* Put images in the assets/images folder.

  **banner for project sites**
  - format: .jpg
  - width: 1280
  - height: 416
   
  **graphics**
  - format: .png
  - width: -
  - height: - 
    
* Do not touch the files in the folders that start with an underscore _. 

* Add **social profiles** easily in `_config.yml`.

  - `500px_url`
  - `facebook_url`
  - `github_url`
  - `gitlab_url`
  - `googleplus_url`
  - `instagram_url`
  - `linkedin_url`
  - `pinterest_url`
  - `slack_url`
  - `twitter_url`

# Create a new file 
 
1.	Click on "Add file" and choose "Create new file"  
2. Name your file xxx.md  
3. Add a link/ tab for your file in `_includes/sidebar.html`  
     --> example: `<li><a href="{{ 'xxx' | absolute_url }}">tab name</a></li>`  
     --> important: your file name must match the link name in '  '  
4.	Add the following header to your xxx.md file: 
   - layout: page  
   - title: ...  
   - (permalink: /xxx/ (*optional*))  
   - (image: assets/images/... (*optional*))  
5.	Edit your file  
     --> for HTML or R-Markdown aids look in the stylesheet.md file   
6.	Save your file in the repository  
7. Github will build the site   
     --> If you have edited your file in an external program and Github gives an error message, you have to save the file with encoding UTF-8.

 
