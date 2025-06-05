# Discord Group Archiver
![image](https://github.com/user-attachments/assets/7cfd10d5-98aa-4911-af4d-233db31d5840)

As we know, memories are important but its so easy to lose a discord group, the owner getting banned or by losing access to their account. This is also a way to archive images and files uploaded to discord.

# Features
- **Save messages**
  - *Message format can be changed in the config: `"messages_format": "{display_name} {message} {date} {attatchements}"`*
  - *Can be disabled in the config: `"messages": True/False`*
- **Save leave/join logs**
  - *Message format can be changed in the config: `"logs_format": "{display_name} {action} {date}"`*
  - *Can be disabled in the config: `"logs": True/False`*
- **Save call logs**
  - *Message format can be changed in the config: `"start_call_logs_format": "{display_name} {date}"` `"end_call_logs_format": "{display_name} {durration} {date}"`*
  - *Can be disabled in the config: `"call_logs": True/False`*
- **Save group name history**
  - *Message format can be changed in the config `"group_name_history_format": "{display_name} {old_name} {new_name} {date}"`*
  - *Can be disabled in the config: `"group_name_history": True/False`*
- **Save group image history**
  - *Image names can be changed in the config `"images_name": "{display_name} {format} {name} {size} {date}"`*
  - *Image format can be changed in the config `"images_format": "png|jpg|webp"`*
  - *Image compression can be changed in the config*
  - *Can be disabled in the config: `"images": True/False`*
- **Save group attachement history (videos)**
  - *attachement names can be changed in the config `"attachements_name": "{display_name} {format} {name} {size} {date}"`*
  - *Can be disabled in the config: `"attachements": True/False`*
- **Save pined messages**
  - *Pined message format can be changed in the config: `"messages_format": "{display_name} {message} {date} {attatchements}"`*
  - *Can be disabled in the config: `"messages": True/False`*
- **Schedules compression**
  - *The schedule can be changed inside the config `"compression_schedule": "7d|30m|69y"`*
  - *Can be disabled in the config: `"compression": True/False`*

# Todo
- Save every voice calls as audio files (with one track per user)
- Save every video streams as video files (with compression)
  - In case you forgot to clip.
