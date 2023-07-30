# Group Membership Automation
## Email Groups
![image](https://github.com/ericcames/Group-Automation/assets/99105520/e4c1e86e-e213-4a55-ba27-1be5c8c402e7)
![image](https://github.com/ericcames/Group-Automation/assets/99105520/814153ed-7754-4e30-a24d-796ec0023185)
![image](https://github.com/ericcames/Group-Automation/assets/99105520/01aeb26c-cf72-4251-a090-d24a4857c498)
![image](https://github.com/ericcames/Group-Automation/assets/99105520/6fcfc39b-0bc1-41f2-822a-fccd67ae568d)

<html>
<h4>Notes</h4>
<ul>
  <li>The inventory for the playbook will be the list of mail exchange servers where group changes are made.</li>
  <li>You will need the commands to do adds and subtracts from the target email group.</li>
  <li>You can talk to your upstream systems with the ansible.builtin.uri module or the community.mysql.mysql_query module</li>
  <li>Incremental updates to the target email group are less work for the mail exchange servers.</li>
</ul>
</html>


