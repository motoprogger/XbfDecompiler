ASSEMBLY=	LibXbf.dll

$(ASSEMBLY):
	mcs -recurse:'*.cs' -r:'System.Xml.Linq' -target:library -out:"$(ASSEMBLY)"

clean:
	rm -f "$(ASSEMBLY)"
