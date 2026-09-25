WITH Korea + Japan v5
Critical fix:
- Phrase data is declared as lexical const WITH_PHRASES in the original app.
- v4 incorrectly checked window.WITH_PHRASES, so situation clicks returned without opening.
- v5 uses the actual WITH_PHRASES constant.
- Korea: situation -> Korean phrases -> Korean speech.
- Japan: same situation -> Japanese phrases -> Japanese speech.
- Banner: Translation & Phrase.
