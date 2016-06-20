
**The @path for deeper urls subdirectories**
------------------


----------
The **@path** is a concept i use to replace my the slash **"/"** character in my laravel applications in the **URL** routes path to **"@"** to make my pages one path with a lot of information about the subdirectories and i will like to share with anyone who is interested to apply in his/her applications.

**Note:** This methodology can be applied to any language or framework in respective of the codebase, it only applies to the URL's and supports all programming languages, but in this instruction i will be specific to the laravel framework only.

**For example (The Traditional way)**
www.example.com/register/complete

Using the **@path** typology in your route it will be 

    Route::get('register@complete', function () {
        return view('main_app.completereg');
    });

with depper sub links

**For example (The Traditional way)**
www.example.com/dashboard/user/profile/

Using the **@path** typology in your route it will be

    Route::get('dashboard@user@profile', function () {
            return view('main_app.dashboard.profile');
        });

**Why should i use the @path?**

 - It is way more cooler for your users to understand the deep url paths
 - It make your URLs one page only.
 - Your can add more to this list, if you think it is way cooler just email (udemesamuel256[at]gmail.com)  i will review it and add it to the list. 
