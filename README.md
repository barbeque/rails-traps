=Rails Traps=
This document contains dumb things I've done in Rails that I shouldn't do again. Eventually it should serve as a best-practices guide based around things that new developers will get tripped up by, as well.

==Models==
  - Set both sides of the relationship to nil when destroying a dependent object

==Databases==
  - Always specify column lengths and null:false for columns in DB

==Security==
  - Always use protect_from_forgery where useful

==Migrations==
  - Don't ever use model classes inside database migrations
