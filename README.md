#construcao-de-software-ufg
public enum TipoLogradouro {
    ALAMEDA,
    AVENIDA,
    MARGINAL,
    RUA,
    RODOVIA,
    VIA,
    VIELA,
    TRAVESSA;

    private TipoLogradouro() {
    }
}

public class Logradouro {
    private String nome;
    private TipoLogradouro tipoLogradouro;

    public String getNome() {
        return nome;
    }

    public void setNome(String nome) {
        this.nome = nome;
    }

    public TipoLogradouro getTipoLogradouro() {
        return tipoLogradouro;
    }

    public void setTipoLogradouro(TipoLogradouro tipoLogradouro) {
        this.tipoLogradouro = tipoLogradouro;
    }
}
