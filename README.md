# Windows Command Line Cheat Sheet

This README.md provides a collection of useful command-line commands for Windows users. Commands are categorized for easy reference.

## Table of Contents
- [System Information](#system-information)
- [File and Directory Operations](#file-and-directory-operations)
- [Network Commands](#network-commands)
- [Process Management](#process-management)
- [Disk Management](#disk-management)
- [User Management](#user-management)
- [Miscellaneous Commands](#miscellaneous-commands)
- [PowerShell Commands](#powershell-commands)

## System Information

- **`systeminfo`**  
  Displays detailed configuration information about the computer and its operating system.

- **`ver`**  
  Shows the Windows version.

- **`wmic cpu get name`**  
  Displays the CPU information.

- **`wmic memorychip get capacity`**  
  Displays the installed RAM capacity.

## File and Directory Operations

- **`dir`**  
  Lists the contents of a directory.

- **`cd [directory]`**  
  Changes the current directory to the specified directory.

  
- **`cd ..`**  
  Changes the current directory to the parent directory.

- **`mkdir [directory]`**  
  Creates a new directory.

  
- **`echo. > [fileName]`**  
  create a File ex. => echo. > index.js

- **`rmdir [directory]`**  
  Removes a directory.

- **`del [file]`**  
  Deletes a file.

- **`copy [source] [destination]`**  
  Copies files from the source to the destination.

- **`move [source] [destination]`**  
  Moves files from the source to the destination.

- **`rename [old_name] [new_name]`**  
  Renames a file or directory.

- **`attrib [file]`**  
  Displays or changes file attributes.

## Network Commands

- **`ipconfig`**  
  Displays IP configuration information.

- **`ping [host]`**  
  Tests network connectivity to a specified host.

- **`tracert [host]`**  
  Traces the route to a specified host.

- **`netstat`**  
  Displays active network connections and listening ports.

- **`nslookup [domain]`**  
  Queries DNS to obtain domain name or IP address mapping.

- **`netsh wlan show profiles`**  
  Lists saved Wi-Fi profiles.

- **`netsh wlan export profile name="[profile_name]" folder="[folder_path]"`**  
  Exports a Wi-Fi profile.

## Process Management

- **`tasklist`**  
  Lists all running processes.

- **`taskkill /PID [pid]`**  
  Terminates a process by its PID.

- **`start [application]`**  
  Starts a new process or application.

## Disk Management

- **`diskpart`**  
  Opens the Disk Partitioning utility.

- **`chkdsk [drive:]`**  
  Checks the file system and file system metadata of a volume for logical and physical errors.

- **`format [drive:]`**  
  Formats a disk for use with Windows.

- **`defrag [drive:]`**  
  Defragments and optimizes the specified drive.

## User Management

- **`net user`**  
  Displays a list of all user accounts.

- **`net user [username] [password] /add`**  
  Adds a new user account.

- **`net user [username] /delete`**  
  Deletes a user account.

- **`net localgroup [groupname] [username] /add`**  
  Adds a user to a local group.

- **`net localgroup [groupname] [username] /delete`**  
  Removes a user from a local group.

## Miscellaneous Commands

- **`cls`**  
  Clears the Command Prompt screen.

- **`echo [text]`**  
  Displays a line of text.

- **`pause`**  
  Pauses the execution of a batch file and shows a "Press any key to continue..." message.

- **`exit`**  
  Exits the Command Prompt or PowerShell session.

## PowerShell Commands

- **`Get-Command`**  
  Lists all cmdlets, functions, workflows, aliases installed on your system.

- **`Get-Help [command]`**  
  Provides detailed information about a cmdlet or function.

- **`Set-ExecutionPolicy [policy]`**  
  Changes the user preference for the PowerShell script execution policy.

- **`Get-Process`**  
  Gets a list of processes running on your local computer.

- **`Start-Service [service_name]`**  
  Starts a service.

- **`Stop-Service [service_name]`**  
  Stops a service.

- **`Get-EventLog -LogName [logname]`**  
  Retrieves events from the specified event log.

- **`Get-ChildItem`**  
  Lists the items in a specified location.

- **`Copy-Item [source] [destination]`**  
  Copies an item from a source to a destination.

- **`Remove-Item [path]`**  
  Deletes an item at the specified path.

- **`Set-Location [path]`**  
  Sets the current working directory to the specified path.

## Additional Resources

For more detailed documentation and advanced usage, refer to the [Microsoft Documentation](https://docs.microsoft.com/en-us/).

Feel free to update this document as needed to keep it current with new commands and options.
