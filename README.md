# android_device_lge_d802
LG G2 GSM

Hi guys welcome to my LG D802 Devicetree which I am using for the Multirom project.
This device tree is originally from cyanogenmod and I cherry picked things from blastagator and patrikkt so credits goes to them
and people mentioned by them.

A little guide. To compile this you need to have cm-12 omnirom or some other android 5.0 sourcecode.
I am personally using omnirom so if the cm12 branch is missing some commits then sorry but I will cherry pick it then a.s.a.p. when I have free time.

These are the steps I have done to get it working on omnirom, including the basics. Use your imagination to modify it to your android 5.0 sourcecode

1. Initialize OMNIROM's sourcecode.
2. Repo sync it
3. Copy the local_manifest.xml to .repo/local_manifests/ folder
4. Sync it again... Yeah I know.
5. go to the omnirom's root directory and execute .build/envsetup.sh
6. lunch full_d802.mk 
7. make recoveryimage
8. make multirom_zip

As you might can see I based this little guide also on Blastagator's readme :l but also one of the reasons why I mixed these two
were to ensure 100% safety with the development.
