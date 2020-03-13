![Test diag2](https://raw.githubusercontent.com/1gog/kvm_ansible/master/ANSIBLE.md)
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