# TestesProntos

''' java
	public static void main(String[] args) {

		String nome = "aaabbbbcc";

		Map<String, Integer> map = new HashMap<>();
		for (int i = 0; i < nome.length(); i++) {

			String letra = String.valueOf(nome.charAt(i));

			Integer integer = map.get(letra);
			int quantidade = 0;
			if (integer != null) {
				quantidade = map.get(letra).intValue();
			}
			map.put(letra, ++quantidade);
		}
		System.out.println(map);
	}
'''
