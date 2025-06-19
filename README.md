
import PaypalDonate from "../components/PaypalDonate";

export default function Home() {
  return (
    <main className="p-10">
      <h1 className="text-3xl font-bold mb-4">Apoya NexaChat</h1>
      <p className="mb-4">Tu contribución ayuda a seguir mejorando la experiencia global.</p>
      <PaypalDonate />
    </main>
  );
}
