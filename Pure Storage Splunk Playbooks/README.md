# Pure Storage Splunk Playbooks


Overview

This repository contains play books designed for Pure Storage FlashArray and FlashBlade to enhance threat response workflows. These playbooks automate actions triggered by alerts, such as creating snapshots for volumes or protection groups, ensuring efficient and proactive incident management.
Features
	1. FlashArray Workflows: Automates actions such as taking snapshots of volumes and protection groups in response to alerts. Additionally, it facilitates the removal of local users from the FlashArray, streamlining user management and enhancing security
	2. FlashBlade Workflows: Automates actions such as taking snapshots of the filesystems in response to alerts..
	3. Customizable Playbooks: Tailored to integrate seamlessly with your security environment for streamlined incident response.

Pre-requisites

To use these play books effectively, ensure the following pre-requisites are met:
        1. Custom Lists: Predefine and populate resources such as storage volumes, protection groups, file systems, and user names.These lists establish a proactive foundation for securing critical resources and automating responses.
	2 Containers: Group related artifacts and security events to streamline processing and provide enhanced contextual analysis.
	3 Assets: Act as integration connectors for seamless interaction with external tools and systems, ensuring efficient data flow across workflows like FlashArray or FlashBlade


Pure Storage FlashArray

This workflow enables automated actions in response to alerts generated on Pure Storage FlashArray, which are parsed and analyzed within Splunk Enterprise SIEM and subsequently forwarded to Splunk SOAR for orchestration and response . The workflow is based on the following PureStorage FlashArray documentation.The workflow is based on the following PureStorage FlashArray documentation.
 https://support.purestorage.com/bundle/m_flasharray_release/page/FlashArray/FlashArray_Release/Purity_FA_REST_API_Release_Notes/topics/concept/c_purityfa_rest_api_2x_release_notes.html


Pure Storage FlashBlade

This workflow enables automated actions in response to alerts generated on Pure Storage FlashBlade, which are parsed and analyzed within Splunk Enterprise SIEM and subsequently forwarded to Splunk SOAR for orchestration and response. The workflow is based on the following PureStorage FlashBlade documentation.
 https://support.purestorage.com/bundle/m_flashblade_release/page/FlashBlade/FlashBlade_Release/Purity_FB_REST_API_Release_Notes/topics/concept/c_purityfb_rest_api_2x_release_notes.html


