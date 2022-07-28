# RSCH-PyReportingCShrp
A small class library that enables invocation of Matplotlib functionality from within C# code.

The History: I am a C# programmer and much more comfortable in C# than I am in Python. But Matplotlib was a crucial tool I needed in my doctoral research. For a while I ran my experiments in C#, exported the data, and used a Jupyter notebook to generate reports. Eventually I threw together this class library that would convert my C# data so that they were Python compatible, create a temporary file, and invoke Python as a Process.

The library is a bit hacky, I tailored it to my needs for my research, but I think with a bit of work it could be converted into somethng really useful for C# programmers who want to harness this power of Python.

I should also quickly explain the HTML table generator. I often would test variations in two parameters at a time, and needed a 2-d table of resulting plots. What I found easiest was to save all of the plots with a naming scheme, generate an HTML table that had each image in the correct row and column, and then examine it in a browser and or export it to a PDF. So that class is a bit more specific that the others, and probably needs more work to make it versatile, but I think it's a useful idea so I'm leaving it in.

So, if you care to join me, maybe we can polish this up and provide a really good research tool.

-YN 7/27/2022
