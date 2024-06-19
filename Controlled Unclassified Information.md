alias:: CUI

- Access requirements
	- There's a classification level called CUI // NOFORN that only US Citizens may access. Blue isn't currently set up with access controls at that level of granularity though.
		- If you see anything marked NOFORN, contact security: cui_security@blueorigin.com
	- Otherwise, 3 general requirements
		- Need to know (ack'd by Program Manager or designee)
		  logseq.order-list-type:: number
		- Initial and annual FOUO/CUI training
		  logseq.order-list-type:: number
		- US Person: lawful resident (green card / citizen) or protected person
		  logseq.order-list-type:: number
- CUI Basic vs Specified
	- Basic (NIST 800-71 and 32 CFR part 2002)
		- Covers most CUI we deal with at Blue
		- Generally marked as "CUI" or "Controlled" or legacy markings ("SBU" or "Unclassified//FOUO")
	- Specified
		- Special handling procedures must be followed
		- Marked with a "SP-" prefix
			- Example: CUI // SP-EXPT
				- This means export-controlled and the CUI data must also follow ITAR/EAR controls
		- More details on these specified markings located in the registries below
			- [https://www.archives.gov/cui](https://www.archives.gov/cui)
			- [https://www.dodcui.mil/Home/DoD-CUI-Registry/](https://www.dodcui.mil/Home/DoD-CUI-Registry/)
- [[ITAR]] vs CUI
	- Not all ITAR data is CUI, but some is, when marked with CUI // SP-EXPT
- Physical security
	- Physical needs to be in a locked cabinet/drawer
	- If no longer needed, needs to be destroyed. Shred paper; for other materials contact Government Security
- IT Security
	- Approved locations
		- S:\\CUI
		- IDE
		- InfoSec-approved Sharepoint and Windchill envs
	- File transfer
		- Anything going outside of Blue needs to be encrypted with FIPS 140-2
			- Can use an S/MIME cert through email (request through Help Desk)
			- Or can use SFTP
	- Blue proprietary data is not CUI unless specifically labeled by the 
	  government. Generally CUI is only for stuff developed specifically for a
	  government contract.
- Marking
	- Generally marked on header and footer of document
	- Blue doesn't have authority to mark documents as CUI without gov't endorsement
	- May also have dissemination marking
	- FOUO and SBU markings are legacy and now considered to be CUI Basic
		- Do not need to be re-marked
- Other resources
	- [https://csrc.nist.gov/pubs/sp/800/171/r2/upd1/final](https://csrc.nist.gov/pubs/sp/800/171/r2/upd1/final) - authoritative source on CUI requirements
	- Executive order: [https://obamawhitehouse.archives.gov/the-press-office/2010/11/04/executive-order-13556-controlled-unclassified-information](https://obamawhitehouse.archives.gov/the-press-office/2010/11/04/executive-order-13556-controlled-unclassified-information)
	- Official training: [https://www.cdse.edu/Training/Toolkits/Controlled-Unclassified-Information-Toolkit/](https://www.cdse.edu/Training/Toolkits/Controlled-Unclassified-Information-Toolkit/)
	- FAQ: [https://www.dcsa.mil/Portals/91/Documents/CTP/CUI/21-10-13%20CUI%20FAQ%20FINAL.pdf](https://www.dcsa.mil/Portals/91/Documents/CTP/CUI/21-10-13%20CUI%20FAQ%20FINAL.pdf)
	- NASA overview: [https://nodis3.gsfc.nasa.gov/npg_img/N_PR_2810_0007_/N_PR_2810_0007_.pdf](https://nodis3.gsfc.nasa.gov/npg_img/N_PR_2810_0007_/N_PR_2810_0007_.pdf)
	- Disclosure requirements: [https://www.acq.osd.mil/dpap/dars/dfars/html/current/252204.htm](https://www.acq.osd.mil/dpap/dars/dfars/html/current/252204.htm)