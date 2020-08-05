# ATV1_LP1_Ex1
Multiplos de 2 e 3

import javax.swing.*;
public class Ex_A {
	public int N1 = 0, N2 = 0;
	public void ler() {
		N1 = Integer.parseInt(JOptionPane.showInputDialog(null, "Digite o valor de N1: "));
		N2 = Integer.parseInt(JOptionPane.showInputDialog(null, "Digite o valor de N2: "));
	}
	public void exibir() {
		if (N1 % 2 == 0 && N1 % 3 == 0)
			JOptionPane.showMessageDialog(null, N1 + " é multiplo de 2 e de 3");
		else if (N1 % 3 == 0)
			JOptionPane.showMessageDialog(null, N1 + " é multiplo de 3");
		else if (N1 % 2 == 0)
			JOptionPane.showMessageDialog(null, N1 + " é multiplo de 2");
		else	JOptionPane.showMessageDialog(null, N1 + " não é multiplo nem de 2 e nem de 3");
		if (N2 % 2 == 0 && N2 % 3 == 0)
			JOptionPane.showMessageDialog(null, N2 + " é multiplo de 2 e de 3");
		else if (N2 % 2 == 0)
			JOptionPane.showMessageDialog(null, N2 + " é multiplo de 3");
		else if (N2 % 2 == 0)
			JOptionPane.showMessageDialog(null, N2 + " é multiplo de 2");
		else	JOptionPane.showMessageDialog(null, N2 + " não é multiplo nem de 2 e nem de 3");
		System.out.println();
	}
	public static void main(String[] args) {
		Ex_A x = new Ex_A();
		x.ler();
		x.exibir();
		JOptionPane.showMessageDialog(null, "Programa Finalizado");
		System.exit(0);
	}

}
