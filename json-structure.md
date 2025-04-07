# JSON Structure <!-- {docsify-ignore} -->

> [!WARNING]
> __NO OFFENSIVE LANGUAGE OR ANY INAPPROPRIATE CONTENT THAT COULD HARM THE WEBSITE, THE URL, THE REPOSITORY, AND THE COMMUNITY.__

To contribute in `First Accord`, you must generate a new JSON file in the `contributors` folder by means of a pull request. For instance, if your GitHub username for the pull request is `STICKnoLOGIC`, you should create a file called `sticknologic.json` in the `contributors` folder. The complete path would be `contributors/example.json`.

## Filename

> [!NOTE]
> The JSON file's name must correspond to your GitHub username that you use when submitting a pull request; if it does not correspond, it will be automatically closed and won't be merged into the repository.

your JSON filename must meet the following criteria:

- It must match your GitHub username. 
- Should consist of letters and numbers, written in lowercase, with dashes serving as dividers. 
- has to be a minimum of 1 character. 
- Should have a .json file extension. 

## Examples of Invalid Filenames
> GitHub username: STICKnoLOGIC

- `.json` (filename is less than 1 character)
- `STICKnoLOGIC.json` (filename contains uppercase letters)
- `sticknologic..json` (filename contains consecutive dots)
- `.sticknologic.json` (filename starts with a dot)
- `stick no logic.json` (filename contains a space)
- `$ticknologi{.json` (filename contains a non-alphanumeric character)
- `sticknologic.json.json` (filename contains more than one .json extension)

## Examples of Valid Filenames

> GitHub username: STICKnoLOGIC
- `sticknologic.json`

> Karen44
- `karen44.json`

## Example JSON File
`contributors/sticknologic.json`

```json
{
    "owner":{
        "name":"John Aerial J. Azcune",
        "email":"johnaerial.azcune@STICKnoLOGIC.is-a.dev",
        "github":"https://github.com/STICKnoLOGIC"
    },
    "social":{ 
        "fa-brands fa-facebook":"https://facebook.com/STICKnoLOGIC",
        "fa-brands fa-square-bluesky":"https://bsky.app/profile/sticknologic.bsky.social",
        "fa-brands fa-linkedin":"https://linkedin.com/in/STICKnoLOGIC",
        "fa-brands fa-x-twitter":"https://x.com/STICKnoLOGIC"
    },
    "my_top_resources":{
        "StackOverflow":"https://stackoverflow.com",
        "STICKnoLOGIC's Blog":"STICKnoLOGIC.is-a.dev/blog",
        "Daily.Dev":"https://app.daily.dev"
    },
    "description":"A Web/App Developer | Pixel Artist | A simple stick that want to be a champ",
    "use_github_avatar":true,
    "custom_avatar_url":"",
    "display_float_text":"STICKnoLOGIC"
}
```

## Structure
#### owner (required)
You must provide certain details about yourself in this section. This ensures that you can be reached if necessary. In the owner object, the fields email and name are mandatory. You may include additional details in this object if you wish.
    
- ##### name (required|string)
Your name or how you wish to be addressed.

- ##### email (required|string)
Email address where we can reach you if there are any issues or updates concerning your contribution.

- ##### github (optional|string)
Your GitHub link (the GitHub link must match the one you use when submitting a pull request)


__Example:__
```json
{
    //other value
    "owner":{
        "name":"Display Name You want to show to whole open source community",
        "emai":"your_handle@your_site.TLD",
        "github":"https://github.com/Your-Username"
    }
}
```

#### description(optional|string)
Portray yourself, brag as much as you'd like, exagerate details about yourself. This is solely for documentation purposes and is optional. (default `"This user is lazy enough to not edit this section"`)

__Example:__
```json
{
    // other value
    "description":"A Valuable Information About Me, You can use code snippet like this: <p style=\"snl-p\"> but it will render as is as we escape html string to avoid malicious code injection! </p>. \n\n\n any whitespace/s including tab, space and enter/new line will be removed."
}
```

#### use_github_avatar (requied|bool|default:true)
Show your Github Avatar if `true`; otherwise, use [`custom_avatar_url`](#custom_avatar_url-optionalstring)

__Example:__
```json
{
    //other value
    "use_github_avatar":true //or false
}
```

#### display_float_text (optional|string)
Display and randomly float this text on the [main page](/). This text serves as evidence that you are a contributor of `First Accord`, even if you remove your contributed JSON. It must contain a minimum of 4 characters and cannot exceed 12 characters.

__Example:__
```json
{
    //other value
    "display":"Any_Name" // atleast 4 character and must not exceed to 12 character 
}
```

#### custom_avatar_url (optional|string)
Utilize to display Avatar if the `use_github_avatar` is set to false. If empty, use the GitHub avatar as the default avatar.

__Example:__
```json
{
    //other value
    "custom_avatar_url":"https://valid.path/for/your/avatar/or/pic.png"
}
```

#### social (optional)
A selected collection of your Social Media Profiles. You can include up to 5 social media accounts.

__Usage:__

"`Key`" : "__Value__"

Where `Key` represents the class name of icons from Font Awesome (e.g. `"fa-brands fa-facebook"`), to explore and discover additional icons, [click here!](https://fontawesome.com/search). 

> [!NOTE]
> The Project only accepts `free` icons from Font Awesome. (\*cough\*.. sponsor? Is there anyone?).

While __Value__ is your `Social Media URL`. 

__Example:__
```json
{
    //other value
    "social":{ 
        "fa-brands fa-facebook":"https://facebook.com/your_handler",
        "fa-brands fa-square-bluesky":"https://bsky.app/profile/your_handler",
        "fa-brabds fa-linkedin":"https://linkedin.com/in/your_handler",
        "fa-brands fa-x-twitter":"https://x.com/your_handler"
    }
}
```

#### my_top_resources (optional)
Share the website you visit the most often to learn new information! (Don't be stingy! share it with us!). You may include up to three (3) resources. 

__Usage:__

"`Key`" : "__Value__"

Where `Key` represents the text shown on the main page. 

While __Value__ is the Link/URL. 

__Example:__
```json
{
    //other value
    "my_top_resources":{
        "Daily.Dev":"https://app.daily.dev",
        "Daily.Dev2":"https://app.daily.dev",
        "Daily.Dev3":"https://app.daily.dev"
    }
}
```