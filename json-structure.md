# JSON Structure <!-- {docsify-ignore} -->

To contribute in `First Accord`, you need to create a new JSON file in the `contributors` directory through a pull request. For example, if your GitHub username used to pull request is `STICKnoLOGIC`, you would create a file named `sticknologic.json` in the `contributors` directory. The full path would be `contributors/example.json`.

## Filename

> [!NOTE]
> The name of the JSON file must match your GitHub username that you use when submitting a pull request; if it doesn't match, it will be automatically closed and will not be merged into the main repository. Nonetheless, your JSON filename needs to satisfy the subsequent requirements: 

the filename of the JSON: 

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
        "fa-facebook":"https://facebook.com/STICKnoLOGIC",
        "fa-square-bluesky":"https://bsky.app/profile/sticknologic.bsky.social",
        "fa-linkedin":"https://linkedin.com/in/STICKnoLOGIC",
        "fa-x-twitter":"https://x.com/STICKnoLOGIC"
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
You need to specify some information about yourself here. This is so that you can be contacted if required. In the owner object, the fields name and email are required. You can add more information in this object if you want.
```json
{
    "owner":{
        "name":"Display Name You want to show to whole open source community"
    }
}
```

#### description(optional|string)
Describe yourself, boast all you want, exxagerate things about you. This is purely for documentation purpose and is optional. (default `"This user is lazy enough to not edit this section"`)

#### use_github_avatar (requied|bool|default:true)
Display your Github Avatar if set to `true`, otherwise use [`custom_avatar_url`](#custom_avatar_url-optionalstring).

#### display_float_text (optional|string)
Show and float this text randomly in [main page](/). we display this text as a proof that you are one of the contributers of `First Accord` even you delete your contributed json. (if you change this each pull request, the previous `display_float_text` will be retain) (the more you have successfully merged PR, the higher chance your `display_float_text` will show in main page).

#### custom_avatar_url (optional|string)
Use to show Avatar if the `use_github_avatar` set to false. if empty, use the github avatar as a default avatar.