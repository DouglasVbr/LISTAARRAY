# LISTAARRAY

package arrayl;

import java.util.ArrayList;

public class ArrayL {

    public static void main(String[] args) {
        // CRIANDO OBJ LINTA
        ArrayList<String> lista = new ArrayList<>();

        // ADICIONAR ITENS A LISTA
        lista.add("a");
        lista.add("b");
        lista.add("d");
        lista.add("e");

        // mostrar elementos 
        System.out.println(lista);
        System.out.println("...........................................................");

        // adicionar elemento em determinada posiçao
        lista.add(2, "c");
        System.out.println(lista);
        System.out.println("...........................................................");

    }

}
