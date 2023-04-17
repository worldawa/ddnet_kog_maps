### ALL DDraceNetwork kog maps archives
classified maps and record_maps database
### irregularly updated

## Usage
Compile DDNet-Server with mysql option.
(Tutor:https://github.com/ddnet/ddnet)
Install mysql and import record_maps.sql.
add this to autoexec_server.cfg
```
exec "types/Easy/flexvotes.cfg"
exec "types/Easy/votes.cfg"
```
Use mysql
```
sv_use_sql 1
add_sqlserver r ddnet record ddnet "thebestpassword" "localhost" "3306" 
add_sqlserver w ddnet record ddnet "thebestpassword" "localhost" "3306" 
```
First ddnet is username, second ddnet is database name, "record" is the prefix of table name; "thebestpassword" is password, "localhost" is addresss, "3306" is mysql port

Thanks for @XCWQW1 