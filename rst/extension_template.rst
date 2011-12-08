About This Extension
====================
The extension illustrates how to document other extensions.

.. A description of the extension goes here.  Describe the purpose of
   the extension, what is the extesion used for?

Extension Overview
------------------

Name
    ACME Template Extension
	
Namespace
    http://docs.acme.org/servers/api/ext/template/v1.0

.. The namespace should be unique to your organization. You can't use
   the OS namespace without the approval of the PTL.

Alias
	ACME-TEMP

.. Use a registered prefix.  You can't use the OS prefix without the
   approval of the PTL.

Contact
	Joe Developer <joe@acme.com>
	
Status
	Alpha

.. You can also use BETA or RELEASE above.
   And this will contime
	
Last Update
	2011-11-30

.. You should use format YYY-MM-DD

Dependencies
    OpenStack Compute API v1.1 (2011-09-08)

.. Note that an extension may depend on another extension, in this
   case the parent extension will be listed here as a dependency.
	
Doc Link (PDF)
	http://docs.acme.com/servers/api/ext/acme-temp.pdf
	
Doc Link (WADL)
	http://docs.acme.com/servers/api/ext/acme-temp.wadl

Doc Link (XSD)
    http://docs.acme.com/servers/api/ext/acme-temp.xsd

.. You can provide additional schema links,
   such as JSON schema etc.  Normally, these
   are included in the WADL, if so, you need
   not directly link them here.
	
Short Description
	The extension illustrates how to document other extensions.

Sample Query Responses
----------------------

As shown below, responses to an EXTENSION query in XML or JSON provide basic information about the extension. 

Extension Query Response: XML

.. literalinclude::
   ../docbook/src/docbkx/samples/ext_query.xml

Extension Query Response: JSON

.. literalinclude::
   ../docbook/src/docbkx/samples/ext_query.json


Document Change History
-----------------------

============= =====================================
Revision Date Summary of Changes
yyyy-mm-dd    Describe the change, one line per rev
============= =====================================


Summary of Changes
==================
This extension adds...Lorem ipsum dolor sit amet, consectetur
adipiscing elit.  Etiam eros ipsum, tempor ut laoreet nec,
adipiscing vel eros.  Integer sit amet nibh iaculis sapien
sagittis blandit.

.. Provide an overall summary of the extension.  Give an
   overview of how the extensions works and what capabilities it
   adds.

New Headers
-----------
None.

.. Describe any new headers.

New Action
----------
None.

.. Describe new actions, if any.

New Faults
----------

========================== ===================== =========================
Fault Element              Associated Error Code Expected in all requests?
========================== ===================== =========================
ACME-TEMP:templateConflict 409
ACME-TEMP:notAllowed       403                   YES
========================== ===================== =========================

.. Describe any new faults, if any.  Make sure you specify
   if the fault can be expectid in all requests.

New Resources
-------------

Described in the WADL...

.. You should describe the operations in detail. If possible
   It's recommended you supply a WADL and XML and JSON payloads in
   *separate* files.

New States
----------

None.

.. Describe new states if any

Changes to the Cloud Servers Specification
------------------------------------------
.. Describe any other changes to the OpenStack API.  Be
   explicit about what exactly has changed. It should be
   possible for someone not involved with the development
   of an extension to sit down with a copy of the core API
   specification and the extension specification and
   produce a merged document that clearly specifies how the
   extended API should function.

In section 4.1.1 (List Servers) of the Cloud Servers Specification:
Examples 4.1 and 4.2 should be replaced with Example 2.7
and Example 2.8 below. Lorem ipsum dolor sit amet,
consectetur adipiscing elit.  Etiam eros ipsum, tempor
ut laoreet nec, adipiscing vel eros.  Integer sit amet
nibh iaculis sapien sagittis blandit.

.. Provide examples in XML and JSON

