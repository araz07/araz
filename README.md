old	new	
...	...	@@ -0,0 +1,215 @@
	1	+#################
	2	+## Eclipse
	3	+#################
	4	+
	5	+*.pydevproject
	6	+.project
	7	+.metadata
	8	+bin/
	9	+tmp/
	10	+*.tmp
	11	+*.bak
	12	+*.swp
	13	+*~.nib
	14	+local.properties
	15	+.classpath
	16	+.settings/
	17	+.loadpath
	18	+
	19	+# External tool builders
	20	+.externalToolBuilders/
	21	+
	22	+# Locally stored "Eclipse launch configurations"
	23	+*.launch
	24	+
	25	+# CDT-specific
	26	+.cproject
	27	+
	28	+# PDT-specific
	29	+.buildpath
	30	+
	31	+
	32	+#################
	33	+## Visual Studio
	34	+#################
	35	+
	36	+## Ignore Visual Studio temporary files, build results, and
	37	+## files generated by popular Visual Studio add-ons.
	38	+
	39	+# User-specific files
	40	+*.suo
	41	+*.user
	42	+*.sln.docstates
	43	+
	44	+# Build results
	45	+
	46	+[Dd]ebug/
	47	+[Rr]elease/
	48	+x64/
	49	+build/
	50	+[Bb]in/
	51	+[Oo]bj/
	52	+
	53	+# MSTest test Results
	54	+[Tt]est[Rr]esult*/
	55	+[Bb]uild[Ll]og.*
	56	+
	57	+*_i.c
	58	+*_p.c
	59	+*.ilk
	60	+*.meta
	61	+*.obj
	62	+*.pch
	63	+*.pdb
	64	+*.pgc
	65	+*.pgd
	66	+*.rsp
	67	+*.sbr
	68	+*.tlb
	69	+*.tli
	70	+*.tlh
	71	+*.tmp
	72	+*.tmp_proj
	73	+*.log
	74	+*.vspscc
	75	+*.vssscc
	76	+.builds
	77	+*.pidb
	78	+*.log
	79	+*.scc
	80	+
	81	+# Visual C++ cache files
	82	+ipch/
	83	+*.aps
	84	+*.ncb
	85	+*.opensdf
	86	+*.sdf
	87	+*.cachefile
	88	+
	89	+# Visual Studio profiler
	90	+*.psess
	91	+*.vsp
	92	+*.vspx
	93	+
	94	+# Guidance Automation Toolkit
	95	+*.gpState
	96	+
	97	+# ReSharper is a .NET coding add-in
	98	+_ReSharper*/
	99	+*.[Rr]e[Ss]harper
	100	+
	101	+# TeamCity is a build add-in
	102	+_TeamCity*
	103	+
	104	+# DotCover is a Code Coverage Tool
	105	+*.dotCover
	106	+
	107	+# NCrunch
	108	+*.ncrunch*
	109	+.*crunch*.local.xml
	110	+
	111	+# Installshield output folder
	112	+[Ee]xpress/
	113	+
	114	+# DocProject is a documentation generator add-in
	115	+DocProject/buildhelp/
	116	+DocProject/Help/*.HxT
	117	+DocProject/Help/*.HxC
	118	+DocProject/Help/*.hhc
	119	+DocProject/Help/*.hhk
	120	+DocProject/Help/*.hhp
	121	+DocProject/Help/Html2
	122	+DocProject/Help/html
	123	+
	124	+# Click-Once directory
	125	+publish/
	126	+
	127	+# Publish Web Output
	128	+*.Publish.xml
	129	+*.pubxml
	130	+
	131	+# NuGet Packages Directory
	132	+## TODO: If you have NuGet Package Restore enabled, uncomment the next line
	133	+#packages/
	134	+
	135	+# Windows Azure Build Output
	136	+csx
	137	+*.build.csdef
	138	+
	139	+# Windows Store app package directory
	140	+AppPackages/
	141	+
	142	+# Others
	143	+sql/
	144	+*.Cache
	145	+ClientBin/
	146	+[Ss]tyle[Cc]op.*
	147	+~$*
	148	+*~
	149	+*.dbmdl
	150	+*.[Pp]ublish.xml
	151	+*.pfx
	152	+*.publishsettings
	153	+
	154	+# RIA/Silverlight projects
	155	+Generated_Code/
	156	+
	157	+# Backup & report files from converting an old project file to a newer
	158	+# Visual Studio version. Backup files are not needed, because we have git ;-)
	159	+_UpgradeReport_Files/
	160	+Backup*/
	161	+UpgradeLog*.XML
	162	+UpgradeLog*.htm
	163	+
	164	+# SQL Server files
	165	+App_Data/*.mdf
	166	+App_Data/*.ldf
	167	+
	168	+#############
	169	+## Windows detritus
	170	+#############
	171	+
	172	+# Windows image file caches
	173	+Thumbs.db
	174	+ehthumbs.db
	175	+
	176	+# Folder config file
	177	+Desktop.ini
	178	+
	179	+# Recycle Bin used on file shares
	180	+$RECYCLE.BIN/
	181	+
	182	+# Mac crap
	183	+.DS_Store
	184	+
	185	+
	186	+#############
	187	+## Python
	188	+#############
	189	+
	190	+*.py[co]
	191	+
	192	+# Packages
	193	+*.egg
	194	+*.egg-info
	195	+dist/
	196	+build/
	197	+eggs/
	198	+parts/
	199	+var/
	200	+sdist/
	201	+develop-eggs/
	202	+.installed.cfg
	203	+
	204	+# Installer logs
	205	+pip-log.txt
	206	+
	207	+# Unit test / coverage reports
	208	+.coverage
	209	+.tox
	210	+
	211	+#Translations
	212	+*.mo
	213	+
	214	+#Mr Developer
	215	+.mr.developer.cfg
