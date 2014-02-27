﻿#AspNet.Identity.RavenDB#
/***************************************MK/

This is an adaption of RavenDB.AspNet.Identity,
originally created by ILM Services and David Boike
	  https://github.com/ILMServices/RavenDB.AspNet.Identity

You may follow David's instructions to start from new ASP.NET MVC 5 project, choosing the Individual User Accounts authentication type,
however, in order to reduce overhead, I recommend to start with an empty web project and create the stuff you need or find suitable nuget packages.

This package contains a little bit of refactoring, mainly separating classes, BUILD it, so it's nuget ready and a very little bit of code cleanup.
You may want to use
	AspNet.Identity.Owin
which is built on this package and provides a basic Identity.Owin bundle and takes care of the startup pattern used by OWIN.
