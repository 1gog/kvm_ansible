![Test diag2](https://g.gravizo.com/source/svg/ansible_class?https://github.com/1gog/kvm_ansible/edit/master/ANSIBLE.md)
<details>
<summary></summary>
ansible_class
/**
*@opt commentname
*@note  some note
*/
class Structural{}

/**
*@opt all
*@note Class
*/
class Counter extends Structural {
        static public int counter;
        public int getCounter();
}
class RunningCounter extends Counter{}

ansible_class
</details>