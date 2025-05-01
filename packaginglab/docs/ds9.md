# DS9

> I selected DS9 as a packaging target because it strikes a good balance between simplicity and real-world relevance. Its build process is manageable, and its importance in the research community makes it a meaningful subject for packaging experiments.

---

[SAOImageDS9](https://sites.google.com/cfa.harvard.edu/saoimageds9) is an astronomical imaging and data visualization application developed by the Smithsonian Astrophysical Observatory. It is widely used in the astrophysics community for displaying and analyzing FITS files.

The application is written in C and uses **Tcl/Tk** for its graphical user interface. Tcl (Tool Command Language) is a scripting language, and Tk is its GUI toolkit. This makes DS9 somewhat atypical compared to modern applications, but also relatively self-contained.

The software is relatively straightforward to compile on Unix-like systems, with few external dependencies and a traditional `configure && make` build process.
