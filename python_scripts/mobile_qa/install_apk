import os

parentdir = os.path.dirname(os.path.abspath(__file__))
files_name = [name for name in os.listdir(parentdir) if name.endswith(".apk")]
print files_name
for n, i in enumerate(files_name):
    print "   Install", i, "application" + " (" + str(n + 1) + " from " + str(len(files_name)) + ")"
    os.system('adb install -r ' + parentdir + '/' + i)
    print "++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++"
