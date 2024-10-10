# kanamart

I would like to make an app based on a website called "JP Canada", which aims to provide a convenient mobile platform for Japanese speakers who are interested in exploring opportunities and resources in Canada. It will serve as a comprehensive guide for users, covering key areas such as immigration, buy & sell stuff, jobs, and cultural exchange. In this app, I will focus on the buy & sell marketplace. 

I want to enhance this product because the current jpcanada.com UI is not great, I want to make it more user friendly and fits the current market UI/UX design.

This app I am going to localize with Japanese only because I am only thinking about targeting Japanese audience who lives in Canada

# Features

## Sign in/Login (TBD)
- Users can enter email and password for to sign up or login
- Users can enter the name and profile pictures


## Listing

### **Item list**
Users are able to view a list of items and details that are posted from others. Each item contains information like:
- Cover photo
- Title
- City location
- Price
- Categories


### **Filter**
- Users are able to filter by price range or categories

### **Item detail**
Users can view each items detail
- Date and time
- Category
- Title
- Product description
- User info (if they decide to disclose)
- User email with an embedded text

## Composer
### **Post an item**
- Title
- Categories(clothes, home & kitchen, electronics, etc…)
- Description
- photos(max 5)
- Price range(Free, Under $10, Under $30, etc…)
- Custom range(0 to whatever)
- Show/Hide poster name
- Show/Hide poster location
- Email input (always hidden)

## Search
### **Searching for items**
- Users can search for items by keyword.

## Communications

Depending on the time, the communication feature might be different.

**Option 1** - If time allow, I would like to implement a chat feature where users can communicate within the app

**Option 2** - If we don't implement login, then users are going to communicate via email which is currently what jpcanada.com is doing as well

## Data resources

### **Network**
### List of posts
The app will retrieve a list of `Post` from remote and display on the home page.

### Creation
When users create posts, it will be store in a server.

### User information
The app will retrieve user information from remote.

### **Local**
Currently no plan on storing any information on devices
