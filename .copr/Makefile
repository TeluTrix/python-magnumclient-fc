srpm:
	dnf install -y spectool rpmbuild
	spectool -g -R python-magnumclient.spec
	rpmbuild -bs python-magnumclient.spec --define "_sourcedir $(PWD)" --define "_srcrpmdir $(outdir)"
