### Naming ###
Why GRAM?
- This application is for store pictures. Like instagram. So GRAM.
- 1 gram (1 g) is light. And this application should be light. Light for code and light in use.

### What problem trying to solve that app? ###
I have children. When I work my children spent a couple of hours in kindergarden.
Their teacher trying to inform us - parents how our child spent this time.
Teacher haven't simple way to do that.
Their the most simpler way is put pictures with our children on social media page (like Facebook or Instagram or both!).
Their add this pictures to open page. Everyone can see it. Everyone can comment it. Everyone can download it!
For many parents it's not the problem. But not for me.
I would like to know what my children do in kindergarden. I would like to have their pictures from kindergarden.
But I don't want to share this pictures with all the world!
But now I can allow to put my children picture in social media. Or not. And don't have any picture from their time in kindergarden.
So. I would like to create some app. And that app should fix this problem.

### What it should be? ###
- Kindergardens should has posibility to add kids pictures.
- Parent should has posibility to view pictures.
- Parent can view pictures only from their children group.
- Pictures can be downloadable.
- Parents can comments pictures.
- System must be secure.
- To view picture parent must log in.
- To add picture teacher must log in.

### What technology should I choose? ###
## Backend ##
- Golang
	* It's not necessary to build it as microservice. Application should be small. Monolith.
	* If application can be run on many major OS (Linux, Windows) that will be in plus.

## Frontend ##
UI and UX should allow end users using this application in simple way.
- Simple, fast and intuitive.

I don't have yet strong recomendation to frontend technology. I can choose one of this:
- React with Next.js
	* Seems to be easy to build for web browser.
	* Maybe (I don't check) it's easy to build mobile app.
- Flutter:
	* Multiplatform.
	* Easy to build for mobile, desktop (not necessary!) and web.

It's open for discution if I need mobile app for this solution.

### How to log in? ###
- To make it easy for end users I should allow to login by external provider like Facebook, Google, Twitter or Microsoft.
And maybe that should be the main way to login? As additional I should implement own authentication system.
For users (like teacher) that don't want login by external provider. 
