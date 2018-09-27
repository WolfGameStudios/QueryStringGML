# QueryStringGML
An alternative to GM: 8's execute_string() function featuring a language inspired by SQL

## WIP
This project is a Work in Progress (WIP), Follow along as we develop this extension!

## About
Query String is a Game Maker Studios: 2 extension that brings with it a custom programming language built around GML with the simplicity of SQL.

```
IF ( A == B ) DO
{
  PRINT ( "Test A", fnt_main, SELF ( X ), SELF ( Y ) COLOR ( 255, 0, 255 ) )
}
ELSEIF ( B == C ) DO
{
  DEBUG ( B )
}
ELSE
{
  DEBUG ( "Test %S", C ) THEN
  SCRIPT ( scr_test, "Argument0", "Argument1", 2, 3 )
}
THEN
IF ( A == B AND B == C ) DEBUG ( "Test C" )
```
