# DriverJS

An interface for building (frontend) enterprise management background.

## Motivation

In our company, there are plenty of management backgrounds. Every new business come out, it needs a management background. It costs a lot of duplicated work, such as choosing a UI styling library, front-end framework, state manager, etc. After tech selecting, developer need to structure their application, writing boostrap code.

The most boring work is connecting them. It inspires me that what if we build this kind of front-end applications just like the way we build applications at operation system? For example, we don't need to care about how the operation system schedule all the process, we only need to write the application itself, but the operation system will provide you an API to communicate with other process (*what we called Inter-Process Communication, IPC*). Thus, when we need to communicate between the "applications" (or different UI component), we shouldn't care about what state manager we are using, we should only use the API that provide this ability. 

If we make a "operation system" like it, developers can only focus on application building above the "operation system".

Another example is that when we use Windows, we always install applications. After the installation finished, we will get a possible shortcut icon on the desktop, and a shortcut on the "Start" -> "Program" menu. It just like the menu and the router when we build web application. The developer should care about how their shortcut be bind on desktop? No, this is what the operation system should do. We shouldn't care about the routing in web application building, we should only need to tell the "operation system" some informations (application name, application id, etc.), and the "operation system" will do the dirty work for you.

## Purpose

DriverJS is an interface for building this "operation system". All the "operation system" need to implement from this interface. It's something like the driver of all the "operation system", and what the name came from.

# License

MIT License