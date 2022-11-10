# excel2sqlite

Convert Excel workbooks to SQLite databases. Useful for getting data into a format that be more easily searched and filtered.

# Install

```bash
pip install excel2sqlite
```

# Using

Say you have an Excel file named `ExperimentData.xlsx` that contains two sheets named "Trial 1" and "Trial 2" with columns of data labeled "Time (s)", "Voltage (V)", and "Current (A)".
To convert this to a database, run

```
$ excel2sqlite ExperimentData.xlsx
```

This will create a database file named `ExperimentData.db` that contains two *tables* named "Trial 1" and "Trial 2" with columns of data labeled "Time (s)", "Voltage (V)", and "Current (A)".


