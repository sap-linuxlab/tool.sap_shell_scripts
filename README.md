# tool.sap_shell_scripts
Collection of shell scripts to be used in SAP environments

- sapfile: A program to display SAP file types based on file name patterns or patterns inside a file archive of type rar, zip, or sapcar.
  Requires:
  - `lsar` (contained in the `unar` package from the EPEL RHEL repo)
  - `zipinfo` (contained in the `unzip` RHEL package)
  - `sapcar` (SAP program to handle sapcar files; typical filename: SAPCAR_1115-70006178.EXE)
  
  For displaying the SAP file types supported by the program, use the following command:
```
sapfile -s
```
