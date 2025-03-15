# DrFromage

Project Management for 1337s


## Steps


``` 
==> python3 -m venv venv

==> source venv/bin/activate

==> pip install rich

==> pip install typer

```

## Alternative Steps

* Below steps are using uv (https://docs.astral.sh/uv/)
```
uv venv --python 3.11

source .venv/bin/activate

uv pip install -r requirements.txt
```

## Usage

```
==> source venv/bin/activate
==> pip install -r requirements.txt
==> python dufromage.py --help
Usage: dufromage.py [OPTIONS] COMMAND [ARGS].


==> python dufromage.py show
 Projects! 💻
┏━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┓
┃ #      ┃ Todo                 ┃     Category ┃         Done ┃
┡━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━┩
│ 1      │ Build fullstack      │         Work │           ❌ │
│ 2      │ Build fullstack      │         Work │           ❌ │
│ 3      │ Do cooking           │   Decompress │           ❌ │
│ 4      │ Do cycling           │      Workout │           ❌ │
│ 5      │ Do reading           │        Study │           ❌ │
└────────┴──────────────────────┴──────────────┴──────────────┘
(venv) ~/repos/arunabhdas/githubrepos/dufromage (main) 
==> python dufromage.py complete 2
complete 2
 Projects! 💻
┏━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┓
┃ #      ┃ Todo                 ┃     Category ┃         Done ┃
┡━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━┩
│ 1      │ Build fullstack      │         Work │           ❌ │
│ 2      │ Build fullstack      │         Work │           ✅ │
│ 3      │ Do cooking           │   Decompress │           ❌ │
│ 4      │ Do cycling           │      Workout │           ❌ │
│ 5      │ Do reading           │        Study │           ❌ │
└────────┴──────────────────────┴──────────────┴──────────────┘
(venv) ~/repos/arunabhdas/githubrepos/dufromage (main) 
==> python dufromage.py complete 1
complete 1
 Projects! 💻
┏━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┓
┃ #      ┃ Todo                 ┃     Category ┃         Done ┃
┡━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━┩
│ 1      │ Build fullstack      │         Work │           ✅ │
│ 2      │ Build fullstack      │         Work │           ✅ │
│ 3      │ Do cooking           │   Decompress │           ❌ │
│ 4      │ Do cycling           │      Workout │           ❌ │
│ 5      │ Do reading           │        Study │           ❌ │
└────────┴──────────────────────┴──────────────┴──────────────┘
(venv) ~/repos/arunabhdas/githubrepos/dufromage (main) 
==> python dufromage.py delete 1
deleting 1
 Projects! 💻
┏━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┓
┃ #      ┃ Todo                 ┃     Category ┃         Done ┃
┡━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━┩
│ 1      │ Build fullstack      │         Work │           ✅ │
│ 2      │ Do cooking           │   Decompress │           ❌ │
│ 3      │ Do cycling           │      Workout │           ❌ │
│ 4      │ Do reading           │        Study │           ❌ │
└────────┴──────────────────────┴──────────────┴──────────────┘
(venv) ~/repos/arunabhdas/githubrepos/dufromage (main) 
==> python dufromage.py show
 Projects! 💻
┏━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┓
┃ #      ┃ Todo                 ┃     Category ┃         Done ┃
┡━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━┩
│ 1      │ Build fullstack      │         Work │           ✅ │
│ 2      │ Do cooking           │   Decompress │           ❌ │
│ 3      │ Do cycling           │      Workout │           ❌ │
│ 4      │ Do reading           │        Study │           ❌ │
└────────┴──────────────────────┴──────────────┴──────────────┘
(venv) ~/repos/arunabhdas/githubrepos/dufromage (main) 
==> python dufromage.py add "Do revision" "Study"
adding Do revision, Study
 Projects! 💻
┏━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━┓
┃ #      ┃ Todo                 ┃     Category ┃         Done ┃
┡━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━┩
│ 1      │ Build fullstack      │         Work │           ✅ │
│ 2      │ Do cooking           │   Decompress │           ❌ │
│ 3      │ Do cycling           │      Workout │           ❌ │
│ 4      │ Do reading           │        Study │           ❌ │
│ 5      │ Do revision          │        Study │           ❌ │
└────────┴──────────────────────┴──────────────┴──────────────┘

```

## Screenshots

![](https://raw.githubusercontent.com/arunabhdas/dufromage/main/screenshots/screenshot_1.png)
