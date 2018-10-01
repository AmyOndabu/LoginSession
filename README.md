# LoginSession
*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package login;

/**
 *
 * @author 110607
 */
public class Login {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        JFrame myframe=new JFrame("Login");
        JPanel mypanel=new JPanel();
        JLabel namelabel=new JLabel("Username");
        JLabel namelabel=new JLabel("Password");
        JTextField Username=new JTextField();
        JTextField Password=new JTextField();
        Login.setcolumns(20);
        JButton login=new JButton(Login);
        mypanel.add(namelabel);
        mypanel.add(Username);
        mypanel.add(namelabel);
        mypanel.add(Password);
        mypanel.add(login);
        myframe.add(mypanel);
        myframe.setSize(600,500);
        myframe.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        myframe.setVisible(true);
        
        
        
        
    }
    
}
