const Portfolio = () => {
    return (
        <div className="min-h-screen bg-gray-100 text-gray-900">
            <header className="bg-blue-600 text-white p-5 text-center text-2xl font-bold">
                Mi Portafolio
            </header>
            <nav className="flex justify-center bg-blue-500 p-3">
                <a href="#inicio" className="text-white mx-2">Inicio</a>
                <a href="#sobre-mi" className="text-white mx-2">Sobre mí</a>
                <a href="#proyectos" className="text-white mx-2">Proyectos</a>
                <a href="#contacto" className="text-white mx-2">Contacto</a>
            </nav>
            <section id="inicio" className="p-10 text-center">
                <h1 className="text-4xl font-bold">¡Hola! Soy Eliette Barrios</h1>
                <p className="mt-4">Analista de datos y profesora especializada en reporting y seguimiento del negocio.</p>
            </section>
            <section id="sobre-mi" className="p-10 text-center bg-gray-200">
                <h2 className="text-3xl font-semibold">Sobre mí</h2>
                <p className="mt-4">Soy una profesional con experiencia en el análisis de datos y generación de reportes estratégicos. Mi pasión es transformar datos en información valiosa para la toma de decisiones empresariales.</p>
            </section>
            <section id="proyectos" className="p-10 text-center">
                <h2 className="text-3xl font-semibold">Mis Proyectos</h2>
                <div className="flex flex-wrap justify-center mt-6">
                    <div className="bg-white shadow-md p-5 m-4 w-80 rounded-lg">
                        <h3 className="text-xl font-bold">Dashboard de Ventas</h3>
                        <p className="mt-2">Creación de un dashboard interactivo para el seguimiento de métricas clave en ventas.</p>
                        <a href="#" className="text-blue-600 mt-2 inline-block">Ver más</a>
                    </div>
                    <div className="bg-white shadow-md p-5 m-4 w-80 rounded-lg">
                        <h3 className="text-xl font-bold">Análisis de Tendencias</h3>
                        <p className="mt-2">Estudio de patrones en el mercado para identificar oportunidades de negocio.</p>
                        <a href="#" className="text-blue-600 mt-2 inline-block">Ver más</a>
                    </div>
                </div>
            </section>
            <section id="contacto" className="p-10 text-center bg-gray-200">
                <h2 className="text-3xl font-semibold">Contacto</h2>
                <form className="mt-6 max-w-md mx-auto">
                    <input type="text" placeholder="Tu nombre" required className="block w-full p-2 border border-gray-300 rounded mb-4" />
                    <input type="email" placeholder="Tu correo" required className="block w-full p-2 border border-gray-300 rounded mb-4" />
                    <textarea placeholder="Tu mensaje" required className="block w-full p-2 border border-gray-300 rounded mb-4"></textarea>
                    <button type="submit" className="bg-blue-600 text-white px-4 py-2 rounded">Enviar</button>
                </form>
            </section>
            <footer className="bg-gray-800 text-white p-5 text-center mt-10">
                &copy; 2025 Eliette Barrios - Todos los derechos reservados.
            </footer>
        </div>
    );
};

export default Portfolio;
