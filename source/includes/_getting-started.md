# Getting Started

Welcome to the InkCloud Theme developer's guide. This guide is meant to help utilize the full power of the Ink Cloud templating engine.

## Sandbox FTP Access


```
Host: theme.ftp.inkcloud9.com
Port: 10021
Username: <sandbox-username>
Password: <sandbox-password>
```

You can update your theme files through FTP access.

<aside class="notice">
You must replace <code>Username</code> and <code>Password</code> with your personal credentials.
</aside>


If you don't have an FTP client [Filezilla Client](https://filezilla-project.org/) is a great FTP client. It is also free!




## Theme Folder Structure

### Theme Structure

- assets
- layout
- settings
- templates


#### The _assets_ folder

The _assets_ folder is where all web assets are stored. This includes images, stylesheets, javacript and fonts.

#### The _layout_ folder

The _layout_ folder contains all layout files. Layouts wrap your site and typically contain the common elements such as the header and footer. By default you must have a _theme.twig_ present in your layout folder.

#### The _templates_ folder

The _template_ folder is where your page templates live.

