|debops_logo| `DebOps Contrib <http://debops.org>`_
===================================================

**Additional Ansible roles of the DebOps project**

Welcome. This organization is meant to hold the Ansible roles and playbooks
that are not part of the official `DebOps <http://github.com/debops/>`_
project, but might be integrated with it in the future.

If you have any roles that you would like to add here, you can either create an
issue in this (``debops-contrib``) repository or contact the team at
``#debops`` IRC channel on FreeNode, or through the `mailing list
<https://groups.io/g/debops>`_.

You should be able to import your role to `Ansible
Galaxy`_ under the `debops-contrib <https://galaxy.ansible.com/debops-contrib/>`_ organization.
The role would then be called ``debops-contrib.$your_role``. Remember to rename
your role appropriately and generate a new README indicating its correct name.

Example: debops-contrib.checkmk_server_

DebOps Contrib Playbooks
------------------------

As for the official DebOps project, DebOps Contrib also has a repository
holding playbooks for the roles. The repository is called
`debops-contrib-playbooks`_.

.. |debops_logo| image:: https://debops.org/images/debops-small.png

.. _`Ansible Galaxy`: https://galaxy.ansible.com/debops-contrib/
.. _debops-contrib.checkmk_server: https://galaxy.ansible.com/debops-contrib/checkmk_server/
.. _debops-contrib-playbooks: https://github.com/debops-contrib/debops-contrib-playbooks

..
 Local Variables:
 mode: rst
 ispell-local-dictionary: "american"
 End:
