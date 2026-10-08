# CSC289 Project Setup Notes

## Activate Virtual Environment

Open PowerShell in the project folder and run:

```powershell
.\.venv\Scripts\Activate.ps1
```

After activation, the terminal should show:

```text
(.venv) PS C:\CSC289\CSC289_Kavitha-Jeeva>
```

## Deactivate Virtual Environment

When finished, run:

```powershell
deactivate
```

## Check Python Version

```powershell
python --version
```

## Check Python Location

```powershell
where.exe python
```

The Python path should point to:

```text
.venv\Scripts\python.exe
```