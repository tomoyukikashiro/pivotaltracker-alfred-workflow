
# Alfred Workflow For Pivotaltracker

## Attention

This Workflow only support [Alfred 3](https://www.alfredapp.com/) (does not support v2)

## Features

- Search projects
- Search stories

then you can 

- open them in browser
- copy their URL
- copy their ID

[![https://gyazo.com/f7dc2afa98b7e3b8741547ccd3f6d25a](https://i.gyazo.com/f7dc2afa98b7e3b8741547ccd3f6d25a.gif)](https://gyazo.com/f7dc2afa98b7e3b8741547ccd3f6d25a)


## Download and Install

Download `pivotaltracker.alfredworkflow` from [here](https://github.com/tomoyukikashiro/pivotaltracker-alfred-workflow/releases/latest) and double click it.

## Usage

open alfred then type `pt`.

## Settings

You need `api access token` and set it in this workflow after installing.

### 1 Get token

Copy `API TOKEN` in [here](https://www.pivotaltracker.com/profile)

### 2 Set token

Open this workflow from alfred preference then click `[x]` this button at top right.

[![https://gyazo.com/26aeb52d09d3d23860d46ec9d6328275](https://i.gyazo.com/26aeb52d09d3d23860d46ec9d6328275.png)](https://gyazo.com/26aeb52d09d3d23860d46ec9d6328275)

Set token in `token` coulumn.

[![https://gyazo.com/4817b1148c14db3652326435b6b45224](https://i.gyazo.com/4817b1148c14db3652326435b6b45224.png)](https://gyazo.com/4817b1148c14db3652326435b6b45224)

## For single project user

Regularly, you have to use this workflow like this.

1. open workflow with `pt`
2. select project
3. select menu (e.g. search, copy, open...)
4. select story
5. select menu (e.g. copy, open...)

If you usually use only one project you can skip 1 and 2 steps above using shortcut workflow.

- Click this keyword trigger box
[![https://gyazo.com/f3a17cfd91b91cbf6809bf6a6ac564dd](https://i.gyazo.com/f3a17cfd91b91cbf6809bf6a6ac564dd.png)](https://gyazo.com/f3a17cfd91b91cbf6809bf6a6ac564dd)

- Set trigger keyword (e.g. your project name)
[![https://gyazo.com/1c20b8a1af4cc63a89f10cc26ba4c9c4](https://i.gyazo.com/1c20b8a1af4cc63a89f10cc26ba4c9c4.png)](https://gyazo.com/1c20b8a1af4cc63a89f10cc26ba4c9c4)

- Click this variable box on right side trigger keyword box
- Set project id
[![https://gyazo.com/14dfe7c4e9e2131c57688d1158f8f2df](https://i.gyazo.com/14dfe7c4e9e2131c57688d1158f8f2df.png)](https://gyazo.com/14dfe7c4e9e2131c57688d1158f8f2df)

# Reference

- https://www.pivotaltracker.com/help/api/rest/v5
- https://www.alfredapp.com/help/workflows/
